<p align="center">
  <a href="https://cooltext.com"><img src="https://images.cooltext.com/5731610.png" width="414" height="98" alt="Irfan Nabil" /></a>
</p>

# My Personal Mobile Shop E-Commerce Website

<p align="center">
  A complete E-commerce Website built with PHP and MySQL Database for learning and development.
</p>

## Overview

Welcome to my personal Mobile Shop E-commerce Website project! This project demonstrates how to create a mobile shop using PHP and a MySQL Database. It starts with an HTML template, converts it into PHP, and then uses a MySQL database to fetch and display products.

## Setup Database

Firstly, import the database from `mobileshop.sql` (located in this project's root folder).

Next, navigate to `func/DBConnect.php` (around line 6), and change the following information to match your database setup:

```php
protected $host = 'localhost';
protected $user = 'root';
protected $password = '';
protected $database = 'mobileshop';

Demo Pages
Here are some of the pages available in this project:

Homepage (Once running locally)
Cart
Product
Login
Register
Account
Manage

How to Run the Server
1. Install XAMPP (or WAMP/MAMP): 
Make sure you have XAMPP installed and Apache and MySQL services are running.

2. Place Project Files: Clone this project into your web server's document root (e.g., C:/xampp/htdocs/ for XAMPP).
Example: C:/xampp/htdocs/my-php-mobile-shop/

3. Configure Database: Follow the steps in the Setup database section above.

4. Access in Browser: Open your web browser and navigate to http://localhost/<your_project_folder_name>/index.php (e.g., http://localhost/my-php-mobile-shop/index.php).

Stay in touch
Author - Irfan Nabil
My GitHub - https://github.com/Irfvnn64