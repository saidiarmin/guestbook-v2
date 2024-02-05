Symfony Guestbook Application
========================

Installation
------------

- `symfony serve -d`
- `symfony composer install`
- `docker compose up -d`
- `symfony console d:m:m`


Consume messenger commands
--------------------------

- `symfony console messenger:consume async -vv`

OR to let it runs in the background

- `symfony run -d --watch=config,src,templates,vendor symfony console messenger:consume async -vv`