---
---

Restore backupwordpress -How to restore from backupwordpress plugin

Posted by SmlCodes

How to restore from backupwordpress plugin

Go to your WordPress page download latest backup

It will downloads a Zip file Extract it. We have to edit wp-config.php & .sql files

Open wp-config.php , change the mysql configurations like dbname, username , password etc

wp-config.php

define('DB\_NAME', 'smlcodes');

/\*\* MySQL database username \*/

define('DB\_USER', 'root');

/\*\* MySQL database password \*/

define('DB\_PASSWORD', 'root');

/\*\* MySQL hostname \*/

define('DB\_HOST', 'localhost:3336');

/\*\* Database Charset to use in creating database tables. \*/

define('DB\_CHARSET', 'utf8');

/\*\* The Database Collate type. Don't change this if in doubt. \*/

define('DB\_COLLATE', '');

\*make sure that new database must be exist

Open database-xxx.sql file and find & replace old domain name to new domain name in case if your changing domain name

Load the .sql file using any MySQL tool like phpmyAdmin/HeildSql execute all sql quires to mentioned data base

Open domainname.com/wp-admin/install.php in your browser. It will take you through the process to set up awp-config.php file with your database connection details.

If for some reason this doesn’t work, don’t worry. It doesn’t work on all web hosts. Open up wp-config-sample.php with a text editor like WordPad or similar and fill in your database connection details.

Save the file as wp-config.php and upload it.