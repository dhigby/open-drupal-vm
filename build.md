VirtualBox 4.3.16
Guest: Ubuntu 12.04.5-desktop-amd-64
Host: Windows 7

* Install guest additions
* sudo su
* apt-get update
* apt-get upgrade
* apt-get install tasksel
* tasksel install lamp-server
* add-apt-repository ppa:webupd8team/sublime-text-2
* apt-get update
* apt-get install php5-curl php5-gd php5-mcrypt phpmyadmin git-core sublime-text curl
* curl -sS https://getcomposer.org/installer | php
* mv composer.phar /usr/local/bin/composer
* composer global require drush/drush:6.*
* mkdir /home/opendrupal/sites
* chown opendrupal:www-data /home/opendrupal/sites
* (change /etc/apache2/sites-available/default from /var/www to /home/opendrupal/sites)
* create vhost for drupal1 & edit /etc/hosts
* Install Drupal at ~/sites/drupal1
