A simple PHP Router.


## Description

With this router you can call a particular route like this:


```php
$router = new Router(new Request);

$router->get('/', function () {
    return <<<HTML
  <h1>Hello world</h1>
HTML;
});
```


## Usage

```sh
php -S 127.0.0.1:8000
```