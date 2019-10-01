MySQL, MariaDB or Percona Server (Recommended)
Required MySQL 5.5.3/MariaDB 5.5.20/Percona Server 5.5.8 or higher with InnoDB as the primary storage engine, and requires the PDO database extension.
Note 1: MySQL 8 is supported only on Drupal 8.6 
Note 2: Drupal itself will generally operate with a default MySQL configuration. A more complex site will likely require configuration changes for the database. 

Web Server
Drupal 8 works on any web server with a version of PHP that meets the PHP version requirements.

File and folder permissions
Drupal and PHP should have read and write access to the /sites/default/files directory. This area is used to store cached files (compressed CSS and JavaScript) and any file uploads through the Drupal interface

Apache
Apache is the most commonly used web server for Drupal. Drupal will work on Apache 2.x hosted on UNIX/Linux, OS X, or Windows.
The majority of Drupal development and deployment is done on Apache, so there is more community experience and testing performed on Apache than on other web servers.

PHP requirements
Required 7.3, as of Drupal 8.6.4
Drupal will work on all supported PHP versions. Recommended PHP versions are the best choice for building a Drupal site because they will remain supported longer. PHP 7 also has significant speed and caching improvements. PHP 5.5, 5.6 and 7.0 have already reached their official end-of-life at the end of 2018, and PHP 7.1 will reach end-of-life before the end of 2019. (See PHP: supported versions for more information.) Drupal 8 will drop support for PHP 5.5 and 5.6 on March 6, 2019. We recommend updating to at least PHP 7.2.

Database
Use one of the following databases:
MySQL - 5.5.3 (MariaDB 5.5.20, Percona 5.5.8) or higher with an InnoDB-compatible primary storage engine
PostgreSQL - 9.1.2 or higher
SQLite - 3.4.2 or higher. Temporary local demo sites use SQLite, which is distributed as part of PHP and doesn’t require installing separate database software.

Browser requirements
Internet Explorer 6.x and later
Microsoft Edge
Firefox 5.x and later
Opera 12 and later
Safari 5.x and later
Google Chrome

