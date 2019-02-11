# hello-world
Linux Tutorial Project

*Installation of Ubuntu

1. Installed ubuntu 18.04.1 on HyperV
2. Created a clone using the GUI on HyperV
3. Installed LAMP
	a. sudo apt-get update
	b. sudo apt-get install lamp-server^


*Wordpress database initialization
#sudo mysql -u root -p


*Create WordPress Database
Commands
1. CREATE DATABASE wordpressdb;
2. CREATE USER wduser@localhost IDENTIFIED BY 'wdpasssafe';
3. GRANT ALL PRIVILEGES ON wordpressdb.* TO wduser@localhost
4. FLUSH PRIVILEGES;
5. exit


* Installing Wordpress
1. cd /tmp
2. sudo wget http://wordpress.org/latest.zip
3. sudo chown -R www-data:www-data /var/www/html/wordpress
4. sudo chmod -R 755 /var/www/html/wordpress
5. mkdir -p /var/www/html/wordpress/wp-content/uploads
6. chown -R www-data:www-data /var/www/html/wordpress/wp-content/uploads

Open web browser
1. http://ipaddress/wordpress
