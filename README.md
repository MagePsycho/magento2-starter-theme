# Magento 2 Starter Theme

##  Overview
This theme is boilerplate/starter theme for Magento 2 based on luma.

## Features
* Coming soon

## CheatSheet
Responsive Media Queries  
[https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/responsive-web-design/rwd_css.html](https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/responsive-web-design/rwd_css.html)

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

## Utility Extensions
After starter theme installation, you may also like to install 
- https://github.com/MagePsycho/magento2-easy-template-path-hints

## Changelog
...


## Need Support?
If you encounter any problems or bugs, please create an issue on [GitHub](https://github.com/MagePsycho/magento2-starter-theme/issues).
OR
You can send an email to magepsycho[at]gmail.com OR submit the [Contact Us](https://www.magepsycho.com/contact) form in case you need any kind of assistance, support and quotation.

## Contribution
Any contribution to the development of Magento 2 Easy Template Path Hints is highly welcome. 
The best possibility to provide any code is to open a [pull request on GitHub](https://github.com/MagePsycho/magento2-starter-theme/pulls).


## References
### Tutorials

* https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/theme-best-practice.html
* https://devdocs.magento.com/guides/v2.3/frontend-dev-guide/themes/theme-overview.html (All Chapters)
* https://jamersan.com/lets-get-started-theming-magento-2-part-1/
* https://jamersan.com/super-guide-theming-magento-2-part-2-3/
* https://jamersan.com/super-guide-theming-magento-2-part-3-3/
* https://www.classyllama.com/blog/a-look-at-css-and-less-in-magento-2 
* https://inchoo.net/magento-2/working-with-css-in-your-first-magento-2-project/
* https://github.com/daniDLL/magento2-frontend
* https://www.youtube.com/playlist?list=PLwcl8DqLMv9f6Ygxgg-_Vk-UdY9FDhpQ_

### Themes

* https://github.com/DivanteLtd/magento2-rapid-theme
* https://github.com/rocketweb-fed/magento2-theme-prime
* https://github.com/SnowdogApps/magento2-alpaca-theme
* https://github.com/studioemma/magento2-theme-optimus
* https://github.com/thebreakfastcowboy/ibec-magento2-theme
* https://github.com/webgriffe/theme-bootstrap
* https://github.com/czone-tech/magento2-theme-fresh
* https://github.com/mcspronko/magento-2-pronko-consulting-theme
* https://github.com/SundialBrands/SheaMoisture2.0-Magento2-Theme
* https://github.com/swissup/theme-frontend-absolute
* https://github.com/ubertheme/magento2_free_theme_trex
* https://github.com/elevinskii/magento2-theme-deepfish
* https://github.com/MykolajKrusser/magento2-theme



