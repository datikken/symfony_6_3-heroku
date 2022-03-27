# HEROKU:
1. API - https://cryptic-scrubland-89996.herokuapp.com
2. FRONT - https://aqueous-sands-86278.herokuapp.com
# Local start
1. docker-compose build --pull --no-cache
2. docker-compose up -d
# Logs:
docker-compose logs -f
# Links:
1. https://localhost
2. https://localhost/docs
3. https://localhost/admin/
# Manage server files:
cd /api <br/>
heroku run bash
# Migrations:
heroku run php bin/console doctrine:migrations:migrate

# Book:
```
{
  "isbn": "9781782164104",
  "title": "Persistence in PHP with the Doctrine ORM",
  "description": "This book is designed for PHP developers and architects who want to modernize their skills through better understanding of Persistence and ORM.",
  "publicationDate": "2013-12-01"
}
```
# Review:
```
{
  "book": "/books/1",
  "rating": 5,
  "body": "Interesting book!",
  "created": "2022-03-27T18:53:29.789Z",
  "updated": "2022-03-27T18:53:29.789Z"
}
