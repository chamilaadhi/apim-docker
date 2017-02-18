# Getting started

All the configuration files can be found in `carbon/repository/conf` location. Modify it before building the docker image

Add `mysql-connector-java-5.1.34-bin.jar` to the artifacts location. If different mysql client is used, please update it in the `Dockerfile`

Use following commands to build the image 

```bash
docker login docker.wso2.com

docker build -t am-analytics .
```

