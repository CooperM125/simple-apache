# simple-apache

This is a simple docker file and index.html file to test docker.

## How to run

The commands to run this simple tomcat server are as follows.

```
docker build -t tomcat-test .
docker run tomcat-test -p 8080:8080 
```