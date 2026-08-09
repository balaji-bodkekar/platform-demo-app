# Platform Demo Application

A simple Flask application used to build an Internal Developer Platform.

## Endpoints

- `/` - Application endpoint
- `/health` - Health check

## Run locally

```bash
python app.py

#Run with Docker

docker build -t platform-demo:1.0 .
docker run -p 8080:8080 platform-demo:1.0