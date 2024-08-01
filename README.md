# dockerize-node-app
## simple Dockerfile example to run a node app 

### to build image 
```
docker bulid -t imagename:tag .
docker run  -p 8080:8080 imagename:tag
```


### test if it is working
```
curl localhost:8080
```

