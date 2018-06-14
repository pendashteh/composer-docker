As a PHP developer you need to use `composer` every now and often. But what if you are using Docker for all dev related stuff and don't want to install `php` just because of Docker?

# Install
```
$ docker pull composer
```

# Use
Use `composer-docker` as you would be using `composer`!
```
$ composer-docker require phpmailer/phpmailer
```

Tip: you can even set `composer` as an alias to `composer-docker`.
