<h1> Data for install project </h1>
1) Install project <br>
    <div style="margin-left: 20px">1.1) ssh: git clone git@github.com:Reable/tall-areas-training.git</div>
    <div style="margin-left: 20px">1.2) https: git clone https://github.com/Reable/tall-areas-training.git</div>
2) Install packages <br>
    <div style="margin-left: 20px">2.1) composer install</div>
    <div style="margin-left: 20px">2.2) npm install</div>
3) Create DB "tallLaravel" <br>
    <div style="margin-left: 20px">3.1) CREATE DATABASE tallLaravel;</div>
4) Create migrations <br>
    <div style="margin-left: 20px">4.1) php artisan migrate</div>
5) Create super user for admin panel "filament" <br>
    <div style="margin-left: 20px">5.1) php artisan make:filament-user</div>
    <div style="margin-left: 20px">5.2) Use data "admin", "admin@gmail.com", "112233"</div>



## License

The Laravel framework is open-sourced software licensed under the [MIT license](https://opensource.org/licenses/MIT).
