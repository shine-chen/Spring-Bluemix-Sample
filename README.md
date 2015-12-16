
# Getting Started

## Execute developing server at local machine.

To run the developing server at your local machine, just execute 
```
grale/tasks/application/bootRun
```
After the local web server is launched, you can test it by opening http://localhost:8080 in a local web browser.

## Packaging JAR and WAR
execute gradle/tasks/build/build

## Deploy WAR
```
cf push <Space-Name> -p build/libs/<The-WAR-Package>.war
```

# References
[https://www.ng.bluemix.net/docs/#starters/liberty/index.html](Liberty for Java)
[http://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/#build-tool-plugins-gradle-packaging](Packaging executable jar and war files)
[http://docs.spring.io/spring-boot/docs/current/reference/htmlsingle/#howto-create-a-deployable-war-file](Create a deployable war file)
