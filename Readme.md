# Django App: Simulating Email Sending with Celery and Redis

This project demonstrates how to use Celery with Redis as a message broker to simulate sending emails in a Django application.

## Features
- Asynchronous email sending using Celery.
- Redis as the message broker for task queuing.
- Example configuration for local development.

## Requirements
- Python 3.x
- Django
- Celery
- Redis

## Setup Instructions

1. **Clone the Repository**
    ```bash
    git clone https://github.com/iAmKabiru/django_celery.git
    cd django_celery
    ```

2. **Install Dependencies**
    ```bash
    pip install -r requirements.txt
    ```

3. **Start Redis**
    Ensure Redis is running locally. You can start it with:
    ```bash
    redis-server
    ```

4. **Run Celery Worker**
    Start the Celery worker:
    ```bash
    celery -A django_celery worker --loglevel=info
    ```

5. **Run the Django Server**
    Start the Django development server:
    ```bash
    python manage.py runserver
    ```

## License
This project is licensed under the MIT License.

## Acknowledgments
- [Django](https://www.djangoproject.com/)
- [Celery](https://docs.celeryproject.org/)
- [Redis](https://redis.io/)

