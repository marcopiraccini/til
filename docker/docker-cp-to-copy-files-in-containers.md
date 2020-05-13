# Docker cp to copy files in containers 

If you need to copy a file to (or from) a container, one option is to use `docker cp`, e.g.:

```
docker cp ./main.js containerName:main.js
```

See [official documentation](https://docs.docker.com/engine/reference/commandline/cp/) for more options
