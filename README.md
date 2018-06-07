# Notes:
- only work for mygit.dhms.net domain name.
- change docker-compose.yml and mygit.toml to use new domain name


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
