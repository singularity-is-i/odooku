web: odooku --database-maxconn 10 --redis-maxconn 10 wsgi $PORT --workers 2 --threads 10
worker: odooku --database-maxconn 5 --redis-maxconn 5 cron --workers 2
