web: php artisan config:cache && php artisan storage:link && php artisan serve --host=0.0.0.0 --port=8000
queue: php artisan queue:work --tries=3
reverb: php -d max_execution_time=0 -d memory_limit=-1 artisan reverb:start --host=0.0.0.0 --port=8080
