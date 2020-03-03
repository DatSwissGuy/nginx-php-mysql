# Simple NGINX, PHP and MySQL Docker Compose

## Filestructure: 

 `/public/index.php` (Local) maps to `/application/public/index.php` (Container)

The folder `/application` inside of the container is not accessible via any http methods (Browser, Postman and so on...). This is useful if you use a php framework like Laravel where you only want to expose the public/published parts. 

So if you want to access your files via Browser they have to be in the `public` folder.

# TODO's
Finish this readme file :)
