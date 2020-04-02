# Wordpress & Docker

This file will setup Wordpress, MySQL & PHPMyAdmin with a single command.

Please change `template.env` to `.env` and set your own user & password etc...

```bash
$ docker-compose up -d

# To Tear Down
$ docker-compose down

# To Tear Down (include volume)
$ docker-compose down --volume
```
