build:
    docker-compose up -d --buld

applies_fixture_db:
    docker-compose exec web python manage.py loaddata fixtures.json
    docker-compose exec web python manage.py migrate