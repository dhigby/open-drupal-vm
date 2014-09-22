# Open Drupal VM

## Quick start

1. Install VirtualBox 4.3.16+
2. Download .oma file and go to 'File -> Import appliance'
3. The default drupal site is available at http://drupal.local and installed at /home/opendrupal/sites/drupal1

## Description

A lightweight but professional ready to use virtual development environment for Drupal. The Open Drupal VM is a pre-configured virtual machine image built on Ubuntu 12.04 (Desktop 64bit) that comes with everything you need to start developing with Drupal 7.

We've designed this VM to use to quickly set up a development environment when running training sessions on Windows computers. It could just as easily be used by a professional Drupal developer or someone starting Drupal development.

It comes with the following:

* Ubuntu 12.04.05 Desktop 64bit
* PHP5.3
* Apache
* MySQL 5.5
* PHPMyAdmin
* Git
* Drush 6.x
* Vim
* Sublime Text 2
* php5-gd, php5-curl, php5-mcrypt (Drupal requirements)
* Webroot in home directory for easy backups
* A fresh copy of Drupal installed at http://drupal1.local

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

## Requirements

* PC with 4GB RAM
* VirtualBox 4.3.16

## Testing

The Open Drupal VM has been tested with Windows 7 host machines.

## FAQ

__Why not Vagrant?__
Vagrant requires more time setting up on Windows machines, and in a training room with limited time a VirtualBox image is quick and simple to import. We also had a few issues getting Vagrant to work consistently on Windows.

__Hasn't this been done already?__
There are projects such as QuickStart and DrupalPro which do very similar things. We wanted something with less installed by default and that had all the latest updates applied, for speed on lower end machines and to keep things simpler for training.

__Where's the VM image?__
We currently don't have hosting for the VM image, but we would like hosting! So if you know anywhere we can host the image, or would like to offer to. Please get in contact with [http://twitter.com/hedley_smith](@hedley_smith)!

## TODO

* Provide a shell script to install Ruby, RVM, Bundler, Sass, Compass, NodeJS, Yeoman / Grunt for frontend devs.
