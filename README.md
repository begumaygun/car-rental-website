# car-rental-website

Car Rental Website
This project is a Car Rental system built with PHP, MySQL (via phpMyAdmin), HTML, CSS, and JavaScript. It allows users to view available cars, and if a car is rented, it updates the stock by reducing the available cars in the database.

Features
View Available Cars: Users can browse a list of available cars.
Car Rental: When a car is rented, it will be marked as unavailable and will be removed from the available stock.
Database Management: The system uses a MySQL database to store car information and rental status.
Admin Panel: Admins can manage cars and rentals.


Requirements
XAMPP (or any PHP and MySQL environment)
phpMyAdmin for database management
Web browser (Chrome, Firefox, etc.)
Setup and Installation
Clone the Repository:

```bash
git clone https://github.com/yourusername/car-rental-website.git
```
Install XAMPP:
Download and install XAMPP on your computer.

Start Apache and MySQL modules from the XAMPP control panel.

Set Up the Database:
Open phpMyAdmin from the XAMPP control panel.

Create a new database (e.g., car_rental_db).
Import the data.sql file (found in this repository) to set up the database tables.

Configure Database Connection:
In the register.php file, update the database credentials if necessary:
php
```php
<?php
$host = 'localhost';   // Database server
$username = 'root';     // Database username
$password = '';         // Database password (default is empty for XAMPP)
$database = 'car_rental_db'; // Database name
?>
```
Access the Website:
open RentFromKAM.html
You should now be able to access the car rental website.

How it Works
Homepage: Displays a list of cars available for rent.
Car Rental: When a user rents a car, the system checks the availability in the database. If available, the car's status is updated to "rented" and the stock count is decremented.
Database: The car details, such as name, model, price, and availability, are stored in the database. phpMyAdmin is used for managing this database.

Technologies Used
Frontend: HTML, CSS, JavaScript
Backend: PHP
Database: MySQL (via phpMyAdmin)
Local Development Environment: XAMPP
Contributing
If you'd like to contribute to this project, feel free to fork the repository, create a new branch, make your changes, and submit a pull request.

License
This project is licensed under the MIT License - see the LICENSE file for details.

## Authors
- **[Begüm Aygün]** - https://github.com/begumaygun
- **[Mehmetcan Kılınç]** - https://github.com/mehmtcankilnc
- **[Emrehan Mart]** - https://github.com/EmrehanMart
