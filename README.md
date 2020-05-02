# Docker Compose: NGINX, PHP and MySQL 

## Filestructure: 

 `/public/index.php` (Local) maps to `/application/public/index.php` (Container)

The folder `/application` inside of the container is not accessible via any http methods (Browser, Postman and so on...). This is useful if you use a php framework like Laravel where you only want to expose the public/published parts while the main application works its magic. 

So if you want to access your files via Browser they have to be in the `public` folder.

Excuse my lack of terminology, i'm still learning the correct words ;)

# TODO's
Finish this readme file :)
