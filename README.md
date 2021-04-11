# laravel-docker-nginx
Docker configuration for Laravel using PHP,  Nginx and Supervisor. Xdebug included.

In dev environment:

```
make up
```
wait and you are ready to go!
#

In production you can build your image like this:

```
docker build --build-arg APP_ENV=production -t yourtag:0.0.1 .
```

In prod Xdebug is not installed and configs are cached.
