# L02 - Flask Redis Application

## Project Description

This project is a Flask web application connected to Redis.

The application uses Docker and Docker Compose to run the services.

## Technologies

- Python
- Flask
- Redis
- Docker
- Docker Compose
- Nginx

## Project Structure

- `main.py` - Main Flask application
- `requirements.txt` - Python dependencies
- `Dockerfile` - Docker image configuration
- `docker-compose.yml` - Docker services configuration
- `nginx_default.conf` - Nginx configuration
- `www/index.html` - Web page
- `.env` - Environment variables

## How to Run

Build and start the containers:

```bash
docker compose up --build