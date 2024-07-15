### About Madadi.Uk

This project is a simple personal portfolio web designed with Laravel 11.15. I decided to build a better user interface for my personal website. Feel free to use this project for your own personal portfolio website.

---

### Architecture

This is a simple personal portfolio web designed with Laravel 11.15. I decided to build a better user interface for my personal website. Feel free to use this project for yours.

---

#### Tools used:
- **Laravel 11.15.0**
- **PHP 8.3.9**
- **JavaScript**
- **Bootstrap 5.3**
- **MySQL 8**
- **Nginx**
- **Docker**

---

### How to run the project:

To build the project, run the following command:

docker-compose build
Then enter the following command to run the project:


docker-compose up -d

Now run the following commands in the terminal to install packages and perform database migrations:


docker exec -it madadiuk-app composer install

docker exec -it madadiuk-app php artisan migrate

To enter the container, use the command:


docker exec -it madadiuk-app /bin/bash