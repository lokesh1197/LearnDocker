## Dockerization [Steps in the app directory]

  - Create a `Dockerfile` and enter the steps to be performed while creating the docker image.
  - Build the Docker image by running `docker build -t <app-name> .`.
  
  - To build the image at `hub.docker.com` run `docker build -t <username>/<app-name> .`.
  - Then login with `docker login`.
  - Finally push with `docker push <username>/<app-name>`.
  
### To Run the Docker Container
  ```
  docker run -p <port>:<port> <app-name>
  ```

### To Run Docker Container from Docker hub
  ```
  docker run <username>/ <app-name>
  ```
