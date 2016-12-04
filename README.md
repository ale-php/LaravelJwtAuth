# LaravelJwtAuth


## Intall

in project directory 
 
<!-- language: php -->
~~~
composer install 
npm i
php artesan migrate
~~~

## HowTo

For use Laravel with JWT Auth you, can use Postman for test
in your header, Content-Type application/json, for get a token send for
/login where make the autenticate , after it you get a token.

Then you use  a token in routes with middleware('auth:api') using
Authorization bearer {token}


*** Alexandre E Souza ***