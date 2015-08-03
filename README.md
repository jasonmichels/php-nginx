## Docker PHP Nginx Image
Docker PHP Nginx base image.  This project is a work in progress and will work with basic PHP/Nginx needs.  Work is being done to make this more Laravel friendly.

### Build
To build this image yourself from the code follow these command
```sh
$ docker build -t <name>/php-nginx .
```

### Demo Usage
```sh
$ docker run -d -p 80:80 --link php-fpm:php-fpm --volumes-from data --name php-nginx <name>/nginx
```

### TODO
- Better documentation

### License
This code is maintained by Jason Michels (http://jasonmichels.com) and open-sourced software licensed under the [MIT license](http://opensource.org/licenses/MIT)