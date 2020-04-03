## El nasr 

Online reservation system & booking software 

##### Login API

## Installation Setups

1. setup database in .env file

```` 
DB_DATABASE=el-naser
DB_USERNAME=root
DB_PASSWORD= 
````

 2. Run your database migrations.

````
php artisan migrate

````
3. Run your database seed.

````
php artisan db:seed --class=UsersTableSeeder

````

4. Test with postman.

````
{
"email":"admin@admin.com",
"password":"password"
}

````


