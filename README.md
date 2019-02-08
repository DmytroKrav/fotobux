# Deploy project

Run command in root folder of project: `docker-compose up -d` 

After deploy docker containers, need to run few follows commands: 

1. `docker run --rm -v $(pwd):/app composer install` 
2. `cp .env.example .env` 
3. `php artisan key:generate`