# REST API with Lumen and JWT authentication

# Installation

1. Clone this repo

```
git clone https://github.com/ShiroWorks/Lumen-REST-API-with-JWT-authentication.git
```

2. Install composer packages

```
cd Lumen-REST-API-with-JWT-authentication
$ composer install
```

3. Create and setup .env file

```
make a copy of .env.example
$ copy .env.example .env
$ php artisan key:generate
put database credentials in .env file
$ php artisan jwt:secret
```

4. Migrate and insert records

```
$ php artisan migrate
```
