# Django App: Simulating Email Sending with Celery and Redis

This project demonstrates how to use Celery with Redis as a message broker to simulate sending emails in a Django application.

## Features
- Asynchronous email sending using Celery.
- Redis as the message broker for task queuing.
- Example configuration for local development using Docker Compose.

## Requirements
- Docker
- Docker Compose

## Setup Instructions

1. **Clone the Repository**
    ```bash
    git clone https://github.com/iAmKabiru/django_celery.git
    cd django_celery
    ```

2. **Start the Services**
    Use Docker Compose to start all required services:
    ```bash
    docker-compose up
    ```

3. **Access the Application**
    The Django development server will be available at:
    ```
    http://localhost:8000
    ```

## License
This project is licensed under the MIT License.

## Acknowledgments
- [Django](https://www.djangoproject.com/)
- [Celery](https://docs.celeryproject.org/)
- [Redis](https://redis.io/)

