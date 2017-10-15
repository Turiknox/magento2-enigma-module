# Turiknox Enigma

## Overview

A Magento 2 module that allows you to add social media links in the system configuration, and removes common unused frontend templates via layout XML.

## Requirements

Magento 2.1.*, 2.2.0

## Installation

Copy the contents of the module into your Magento root directory.

Enable the module via the command line:

/path/to/php bin/magento module:enable Turiknox_Enigma

Run the database upgrade via the command line:

/path/to/php bin/magento setup:upgrade

Run the compile command and refresh the Magento cache:

/path/to/php bin/magento setup:di:compile 

/path/to/php bin/magento cache:clean

