As a PHP developer you'd want to use `composer` every now and then. But what if you are using Docker and don't want to pollute your host machine with `php`?!

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
