# Use Node.js without a local installation

Uses a Node.js LTS image and opens a bash shell running on 
the container. Therefore you can use Node.js and npm 
without a local installation.

```
docker compose run --rm --service-ports node_shell
```

- uses Node.js LTS
- maps port 3000
- local folder is mapped to /home/app
- opens bash shell
