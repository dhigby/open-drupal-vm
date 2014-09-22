# Open Drupal VM

A lightweight but professional ready to use virtual development environment for Drupal. The Open Drupal VM is a pre-configured virtual machine image built on Ubuntu 12.04 (Desktop 64bit) that comes with everything you need to start developing with Drupal 7.

We've designed this VM to use to quickly set up a development environment when running training sessions on Windows computers. It could just as easily be used by a professional Drupal developer.

It comes with the following:

* Ubuntu 12.04.05 Desktop 64bit
* PHP5.3
* Apache
* MySQL 5.5
* PHPMyAdmin
* Git
* Vim
* Sublime Text 2
* php5-gd, php5-curl, php5-mcrypt (Drupal requirements)
* Drush 6.x
* Webroot in home directory for easy backups
* A fresh copy of Drupal installed at http://drupal1.local

## Installation

* Install VirtualBox 4.3.16
* Go to 'import appliance'

## Passwords

__Ubuntu__
username: opendrupal
password: opendrupal

__MySQL__
username: root
password: root

__Drupal__
username: admin
password: admin

## Testing

The Open Drupal VM has been tested in Windows 7 host machines.

## FAQ

__Why not Vagrant?__
We tried using 

__Hasn't this been done already?__
Similar to QuickStart or DrupalPro.

## Todo

* Update guest additions to latest version
* Add readme file on desktop
