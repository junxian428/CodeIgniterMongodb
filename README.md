# CodeIgniterMongodb

Downloads:

https://codeigniter.com/

git clone https://github.com/intekhabrizvi/Codeigniter-mongo-library.git


pwd

sudo cp /home/pi/Downloads/Codeigniter-mongo-library-master.zip /var/www/html/tutorial

sudo unzip Codeigniter-mongo-library-master.zip

sudo rm Codeigniter-mongo-library-master.zip


rename:

sudo mv Codeigniter-mongo-library-master demo


sudo cp /home/pi/Downloads/framework-4.1.1.zip /var/www/html/demo

_________________________________________________________________________________________

Check Apache error log:

 cat /var/log/apache2/error.log
 
 __________________________________________________________________________________________
 
 Find php.ini
 
 php --ini

Location: /etc/php/7.3/cli

![alt-text](https://user-images.githubusercontent.com/58724748/106718814-8297f600-663c-11eb-8149-5c425869d40d.png)

![alt-text](https://user-images.githubusercontent.com/58724748/106720624-a5c3a500-663e-11eb-92c7-b3e02c830c69.png)

Check Extension

php -m

Else

sudo apt-get install php-intl

![alt-text](https://user-images.githubusercontent.com/58724748/106723256-e113a300-6641-11eb-9b00-007e8be861b5.png)

chown -R apache /var/www/myproject/writable

________________________________________________________________________________________________________________

Mongodb Install

sudo apt-get install mongodb

_______________________________________________________________________________________________________________

Mongodb Config

sudo cp /home/pi/Downloads/demo/application/config/mongo_db.php /var/www/html/Code/demo/app/Config

sudo cp /home/pi/Downloads/demo/application/libraries/Mongo_db.php /var/www/html/Code/demo/app/Libraries



