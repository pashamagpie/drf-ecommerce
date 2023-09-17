# Django REST Framework Ecommerce App

## Setup

Run all docker containers:
```
docker-compose up -d
```
Connect to main application container and install demo fixtures to simulate database:
```
docker exec -it web_ecommerce /bin/sh
python manage.py demo-fixtures
```

Open your browser to http://localhost:8000 and you should see the browsable version of the API.