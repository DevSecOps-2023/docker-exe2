# docker-exe2
exercice2
```shell
docker build -t tomcat:v1 .
docker images
docker history tomcat:v1
docker  run -d -p 30200:8080 tomcat:v1
docker logs pensive_oitras
```

```shell
in file  tomcat-users.xml
 <role rolename="manager"/>
  <user username="logwire" password="docker" roles="manager"/>

