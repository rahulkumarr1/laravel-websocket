# laravel-websocket
Laravel WebSockets

# Run Queue and WebSockets Server.

** To run Laravel Queue: **

php artisan queue:work

** To run Laravel WebSockets server: **
php artisan websockets:serve

# Configure broadcasting and Websockets.
Update your .env file. Make sure to set PUSHER variables:

```
    BROADCAST_DRIVER=pusher

    PUSHER_APP_ID=staging
    PUSHER_APP_KEY=staging
    PUSHER_APP_SECRET=staging
    PUSHER_APP_CLUSTER=mt1

    LARAVEL_WEBSOCKETS_HOST=127.0.0.1
    LARAVEL_WEBSOCKETS_PORT=6001    	
```
