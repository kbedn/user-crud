Simple User CRUD
========================
Installation:
 
 Create a local clone of [Github kbedn/user-crud](https://github.com/kbedn/user-crud.git)
 
 Browse the project directory and execute 'composer install' [Installing Composer](https://symfony.com/doc/current/cookbook/composer.html)
 
 After composer manage dependencies, cache and base parameters, please execute following commands:
    
    php app/console d:d:c
    php app/console d:s:u --force
    php app/console se:ru

 Then, open your browser and access the http://localhost:8000/ to run simple user crud site.