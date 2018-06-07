# run

```
docker-compose up
```

# add user
```
$ cd /path/to/registryaccess

$ docker run --rm \
  --entrypoint htpasswd \
  registry:2 -Bbn mike 123456 >> auth/htpasswd
```  
