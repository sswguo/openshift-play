#### Build image
```
docker build -t auditquery:1.0 .
```

#### Tag the image
```
docker tag auditquery:1.0 jind0001/auditquery:1.0
```

#### Push the image into the [private registry](https://cloud.docker.com/repository/docker/jind0001/auditquery)
```
docker login
docker push jind0001/auditquery:1.0
```
