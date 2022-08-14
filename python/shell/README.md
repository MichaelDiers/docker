# Use Node.js without a local installation

Uses a latest python image and opens a bash shell running on 
the container. Therefore you can use python 
without a local installation.

```
docker compose run --rm --service-ports python_shell
```

- uses python:latest
- maps port 3000
- local folder is mapped to /home/app
- opens bash shell
