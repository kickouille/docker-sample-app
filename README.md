# Docker Sample Application

A simple Flask app that runs inside a Docker container.

## Build and Run

```bash
# Build the Docker image
docker build -t docker-sample-app .

# Run the container
docker run -p 5000:5000 docker-sample-app
```

Then visit http://localhost:5000 to see the message.