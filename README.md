# Docker Tutorial

This repository contains a simple Docker tutorial project that demonstrates how to build and deploy a containerized application using Docker.

## Prerequisites

Before you begin, ensure you have the following installed on your system:
- Docker: [Installation guide](https://docs.docker.com/get-docker/)
- Git: [Installation guide](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git)

## Getting Started

Follow these steps to build and run the Docker container locally:

1. Clone this repository:
```bash
git clone https://github.com/your-username/your-repository.git
```

2. Navigate to the project directory:
```bash
cd docker-tutorial
```

3. Build the Docker image:
```bash
docker build -t demo:v1 .
```

4. Run the Docker container:
```bash
docker run -p 5000:5000 demo:v1
```

5. Open your web browser and visit http://localhost:5000 to see the application running.
