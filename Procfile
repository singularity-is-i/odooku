web: odooku --database-maxconn 15 --redis-maxconn 15 wsgi $PORT --workers 10 --threads 15
worker: odooku --database-maxconn 5 --redis-maxconn 5 cron --workers 5
