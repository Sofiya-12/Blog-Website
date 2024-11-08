# Laravel-Blog-Website

A straightforward blog page written in PHP/Laravel.

![main](https://github.com/Mati822456/Laravel-Blog-Website/assets/103435077/0968c8ef-77cd-4e7f-ba4b-76e1a8e4388d)

## Table of Contents

-   [General Info](#general-info)
-   [Technologies](#technologies)
-   [Setup](#setup)
-   [Features](#features)
-   [Acknowledgements](#acknowledgements)
-   [Contact](#contact)




![post](https://github.com/Mati822456/Laravel-Blog-Website/assets/103435077/e332038e-05bf-4818-b32d-968a45692d84)

## Technologies

-   Laravel 9.45.1
-   Blade
-   PHP 8.1.7
-   MySQL 8.0.29
-   HTML 5
-   CSS 3
-   JavaScript
- 
## Setup

To run this project you will need to install PHP, MySQL, [Composer](https://getcomposer.org/download/), [NPM](https://www.npmjs.com/package/npm) on your local machine.

If you have everything, you can run these commands:

```
# Clone this respository
> git clone https://github.com/Mati822456/Laravel-Blog-Website.git

# Go into the folder
> cd Laravel-Blog-Website

# Install dependencies from lock file
> composer install

# Install packages from package.json
> npm install

# Compile assets
> npm run build
```

`Create or copy the .env file and configure it. e.g., db_username, db_password, db_database`
</br>
`You will need to configure SMTP in order to send emails.`

```
# Generate APP_KEY
> php artisan key:generate

# Run migrations if you have created database
> php artisan migrate

# Run seeder to create Permissions, Admin and Writer users and 10 random posts
> php artisan db:seed

# Start server
> php artisan serve

# Access using
http://localhost:8000
```

Now you can login using created accounts:

```
Role: Admin
Email: admin@db.com
Password: admin1234

Role: Writer
Email: writer@db.com
Password: writer1234
```

![dashboard](https://github.com/Mati822456/Laravel-Blog-Website/assets/103435077/ab2cbc89-b149-4770-9f90-46fa6287fd8b)
![dashboard_posts](https://github.com/Mati822456/Laravel-Blog-Website/assets/103435077/4c295832-b21c-4f64-bc7f-8da7e73ed3de)
![posts_create](https://github.com/Mati822456/Laravel-Blog-Website/assets/103435077/579c241a-48ee-48fc-8654-f366a3a5f490)



