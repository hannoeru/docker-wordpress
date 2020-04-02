# Wordpress & Docker

This file will setup Wordpress, MySQL & PHPMyAdmin with a single command. Add the code below to a file called "docker-compose.yaml" and run the command.

Please change template.env to .env and set your own user & password etc...

```
$ docker-compose up -d

# To Tear Down
$ docker-compose down

# To Tear Down (include volume)
$ docker-compose down --volume
```

