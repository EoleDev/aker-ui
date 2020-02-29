# Aker UI admin panel to handle Mariadb IDP

This project use aker-ui-server and aker-ui-client.

NOTICE: This project was developed with no concern to security.
As it would be use by admins, it was not a priority.

Use it at your own risk.

## Deploy

If using another webserver than apache, don't forget to implement the rewrite as shown in .htaccess file.

 - Clone this repo
 - Clone the submodule : git submodule update
 - In server dir, install composer dependencies
   - Download composer
   - Run : composer update
 - Create the webserver configuration, you will need php with pdo and mysql extension
 - Edit the server settings : server/app/settings.php and set the parameters for the aker database
 

The UI is accessible at the url /app/ !
