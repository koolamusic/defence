# Microfinance Manager


## INSTALLATION / CONFIGURATION

This is a full web based project that requires a PHP-capable webserver and a MySQL database. For testing purposes, using XAMPP is recommende$


To connect to the test database included in this repository (mangoo.sql), the required configuration is as follows.
Server: 127.0.0.1 /
Database user: root /
Database password: '' (empty password).
These are the current default settings included in ./config/config.php. They should only be used for test installations. Make sure to change dat$

The default login for the program GUI is:
Username: admin
Password: password




#### SETUP DBV
- modify /db/config.php from `line 8` with DATABASE credentials

```
define('DB_HOST', 'localhost');
define('DB_PORT', 3306);
define('DB_USERNAME', 'DB_USERNAME');
define('DB_PASSWORD', 'DB_PASSWORD');
define('DB_NAME', 'DB_NAME');
```

## DATABASE SYNC
- if you are using the database VERSIONING
- visit the url (http://localhost/{PROJECT_DIRECTORY}/dbv)
- input username `dbv` and password `dbv`
- select the option **push to database** to push the sql tables to mysql database
- select the option export to disk to move the database tables to disk


## Features
- Customer management
- Share account management
- Savings account management
- Loan management
- Employee management
- Reporting
- Accounting


## Licence
This software is licensed under the GNU General Public License 3.0, a copy of which can be found in the LICENSE file.
