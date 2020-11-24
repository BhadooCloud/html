### LAMP on Ubuntu - [Source](https://web.archive.org/web/20180323030918/https://howtoubuntu.org/how-to-install-lamp-on-ubuntu) [PHP](https://www.cloudbooklet.com/upgrade-php-version-to-php-7-4-on-ubuntu/)

````
sudo apt-get install apache2
sudo apt-get install mysql-server
sudo add-apt-repository ppa:ondrej/php
sudo apt-get update && sudo apt-get upgrade && sudo apt update && sudo apt upgrade
sudo apt install php7.4
sudo apt install php7.4-common php7.4-mysql php7.4-xml php7.4-xmlrpc php7.4-curl php7.4-gd php7.4-imagick php7.4-cli php7.4-dev php7.4-imap php7.4-mbstring php7.4-opcache php7.4-soap php7.4-zip php7.4-intl -y
sudo service apache2 restart
php -r 'echo "\n\nYour PHP installation is working fine.\n\n\n";'
cd /var/www/html
````

### Rapidleech [RAR Fix](https://github.com/Th3-822/rapidleech/issues/71)

````
cd /var/www/html
````

````
sudo rm -rf rar && sudo wget https://rarlab.com/rar/rarlinux-x64-5.6.0.tar.gz && sudo tar -xvf rarlinux-x64-5.6.0.tar.gz && sudo rm -f rarlinux-x64-5.6.0.tar.gz && sudo chmod -R 777 rar && sudo chmod -R 777 rar/*
````
