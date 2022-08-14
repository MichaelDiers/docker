# One shell to rule them all

Run multiple development environments by using a single docker compose file. Starts a bash shell on the container and maps the local environment.

Supports:
- Node.js
  ```
  docker compose run --rm --service-ports node_shell
  ```

  - uses Node.js LTS
  - maps port 3000
  - local folder is mapped to /home/app
  - opens bash shell
  - Python latest
- Python
  ```
  docker compose run --rm --service-ports python_shell
  ```

  - uses python:latest
  - maps port 3000
  - local folder is mapped to /home/app
  - opens bash shell
