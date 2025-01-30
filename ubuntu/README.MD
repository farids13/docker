
## How to Run This Configuration

### Step 1
Start the services using Docker Compose:
```sh
docker-compose up -d
```

### Step 2
Run an Ubuntu container interactively:
```sh
docker run -it ubuntu

To access the running container, use the following command:
```sh
docker exec -it <container_id> /bin/bash
```
Replace `<container_id>` with the actual ID of your running container, which you can find using:
```sh
docker ps
```
```