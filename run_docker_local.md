``` cmd
docker run -v c:\temp\d:/tmp/src -it --rm mcr.microsoft.com/appsvc/staticappsclient:stable 'bash'

cd /bin/staticsites/
./StaticSitesClient upload --verbose true --apiToken 3872425c666b13b1290693a0514cfc274e3ee179aaa0cf174feb75fad815253f-807961cb-ff20-4c7e-abf1-24f0e0461b5300316939 --workdir /tmp/src --app Client --api Api
```
