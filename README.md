# adminer-oracle-driver
Oracle driver

# Install
[Detailed Information](https://www.adminer.org/en/plugins/)

Download oracle.inc.php file to plugins/drivers folder in your server.

Example folder construction:
```
adminer-folder/
 - adminer.php
 - index.php
 - plugins/
     - drivers/
         - oracle.inc.php
```

Example of index.php:
```php
include_once "./plugins/drivers/oracle.inc.php";
// include original Adminer or Adminer Editor
include "./adminer.php";
