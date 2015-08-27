This is a [penny](https://github.com/gianarb/penny) skeleton application.  
It contains only foldering, no components or other things.  

## Install
```bash
$ git clone git@github.com:gianarb/penny-foldering
$ cd penny-foldering
$ composer install
```

## Foldering
```php
.
├── app
│   └── ..
├── composer.json
├── config
├── public
│   └── index.php
├── README.md
└── vendor
```

* `app` contains application files, Controller, Service, Entity, etc.
* `public` entry point of application.
* `config` default path to load dependency injection configuration.

## WebServer
```bash
$ php -S 127.0.0.0:8087 -t public
```
