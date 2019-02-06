После развертывания и запуска докер необходимо выполнить:

1. docker run --rm -v $(pwd):/app composer install 
2. cp .env.example .env 
3. php artisan key:generate