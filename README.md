# some_docker_config
remove none  
```bash
bashsudo docker rmi (docker images -a| grep "^<none>" | awk '{ print $3 }')
```
