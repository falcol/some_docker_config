# some_docker_config
remove none
```sudo docker rmi (docker images -a| grep "^<none>" | awk '{ print $3 }')```
