``` bash
docker run -v c:\temp\d:/tmp/src -it --rm mcr.microsoft.com/appsvc/staticappsclient:stable 'bash'

cd /bin/staticsites/
./StaticSitesClient upload --verbose true --apiToken 3872425c666b13b1290693a0514cfc274e3ee179aaa0cf174feb75fad815253f-807961cb-ff20-4c7e-abf1-24f0e0461b5300316939 --workdir /tmp/src --app Client --api Api  --outputLocation wwwroot
```

## Commandline Options
```
StaticSitesClient 1.0.0
Copyright (C) 2021 StaticSitesClient

  --verbose                  (Default: false) Enables verbose logging

  --workdir                  (Default: ) Working directory of the repository

  --buildTimeoutInMinutes    (Default: ) Time limit of oryx build in minutes

  --app                      (Default: ) Directory of app source code

  --api                      (Default: ) Directory of api source code

  --routesLocation           (Default: ) Path to the routes file

  --outputLocation           (Default: ) Directory of built application artifacts

  --appArtifactLocation      (Default: ) Directory of built application artifacts

  --event                    (Default: ) Filepath of the event json

  --apiToken                 (Default: ) ApiToken

  --repoToken                (Default: ) RepoToken

  --oryxEnabled              (Default: false) Deprecated

  --appBuildCommand          (Default: ) App Build Command

  --apiBuildCommand          (Default: ) Api Build Command

  --DeploymentProvider       (Default: ) Deployment provider

  --help                     Display this help screen.

  --version                  Display version information.
```
