# Simple NGINX, PHP and MySQL Docker Compose

## Filestructure: 

The folder `/application` inside of the container is not accessible via any http methods, this is useful if you use a php framework like Laravel where you only want to expose the public parts: `/application/public/index.php`.

This means `/public/index.php` maps to `/application/public/index.php

# TODO's
Finish this readme file :)
