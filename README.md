# Magento 2 Starter Theme

##  Overview
This theme is boilerplate/starter theme for Magento 2 based on luma.

## Features
* Coming soon

## Installation

### 1 Using Composer
```
composer config repositories.magepsychostartertheme git git@github.com:MagePsycho/magento2-starter-theme
composer require magepsycho/magento2-starter-theme:dev-master
```

### 2 Using Modman
```
modman init
modman clone git@github.com:MagePsycho/magento2-starter-theme.git
```

### 3 Using Zip File
* Download the [Extension Zip File](https://github.com/MagePsycho/magento2-starter-theme/archive/master.zip)
* Extract & upload the files to `/path/to/magento2/app/design/frontend/MagePsycho/default/`

After installation by either means, enable the extension by running following commands (from root of Magento2 installation):
```
php bin/magento module:enable MagePsycho_Easypathhints --clear-static-content
php bin/magento setup:upgrade
php bin/magento cache:flush
```
[Click here to read more on module packaging, installation & activation in Magento 2](http://www.blog.magepsycho.com/install-magento-2-module-from-github-or-bitbucket-repository-using-composer/)


## Screenshots
...


## Changelog
...


## Need Support?
If you encounter any problems or bugs, please create an issue on [GitHub](https://github.com/MagePsycho/magento2-starter-theme/issues).
OR
You can send an email to magepsycho[at]gmail.com OR submit the [Contact Us](https://www.magepsycho.com/contact) form in case you need any kind of assistance, support and quotation.

## Contribution
Any contribution to the development of Magento 2 Easy Template Path Hints is highly welcome. 
The best possibility to provide any code is to open a [pull request on GitHub](https://github.com/MagePsycho/magento2-starter-theme/pulls).
