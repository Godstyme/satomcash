## SATOMCASH API LARAVEL
This API is built for investment site. You can deploy it in your site.
This project provides the following features:
- CRUD system
- Possible entities: ['admin','users','deposit','withdrawal']
- Use a mailing library to send mail on registration.
- Use a mailing library to send in a forget password URL for resetting password
- Use JWT to authenticate every role based endpoint
- Use a solid principle design
# Database ERD
- https://drawsql.app/teams/godstime/diagrams/investment-site


## Quick Setup ⚙️
First, clone repo and install all dependencies.
```sh
$ git clone https://github.com/Godstyme/satomcash
$ cd satomcash
$ composer install
```
Setup database by creating a database called `satomcasp_db` in your `phpMyAdmin`. This api uses the `satomcasp_db` database as configured in the app `.env` file.
We have to use a migration command to prepare the database migration classes for the target tables.

```sh
$ php artisan migrate
$ php artisan serve
``` 

Don't forget to star the project :)
