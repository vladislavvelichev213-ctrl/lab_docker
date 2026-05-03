# Laboratory work: Docker

## Author
Владислав Величев
GitHub: vladislavvelichev213-ctrl

## Tutorial

### Step 1. Install Docker
Docker installed via Homebrew.
Version: Docker 29.4.1

### Step 2. Create Dockerfile
Created Dockerfile with python:3.9-slim, flask, mysql-connector.

### Step 3. Build and Run
Image built and container ran successfully.
Output: Hello, Docker!

### Step 4. Create docker-compose.yml
Created docker-compose.yml with app and mariadb services.
Port 5000 exposed.

### Step 5. Run docker compose
Both containers started successfully.
MariaDB healthy, app listening on port 5001.

## Homework

### Part I. Docker
- Dockerfile created
- Container built and run
- README.md copied to /home/ inside container
- Connected to container interactively
- Verified file exists in /home/README.md
- Container stopped

### Part II. Docker Compose
- docker-compose.yml created with app + MariaDB
- Web application (Flask + MySQL) works
- Tasks saved to database
- Browser screenshot: screenshot.png
- Accessible at http://localhost:5001

## Links
- Docker Compose: https://docs.docker.com/compose/
- Dockerfile reference: https://docs.docker.com/reference/dockerfile/
