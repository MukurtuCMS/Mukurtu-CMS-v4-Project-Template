# Mukurtu CMS v4 Project Template

## Requirements
* The necessary database server/web server/PHP installed for [Drupal 9](https://www.drupal.org/docs/system-requirements)
* [Composer](https://getcomposer.org/)
* [NPM/Bower Dependency Manager for Composer](https://packagist.org/packages/fxp/composer-asset-plugin)
  * `composer global require "fxp/composer-asset-plugin"`

## Using the template to download Mukurtu CMS v4
* Create a folder (e.g., 'mukurtu4')
* Checkout or download the 'composer.json' file in this repository to your new folder
* Run `composer install` in your new folder. This will download the Mukurtu CMS profile and all required modules
  * Note that during development we are using our private repository to serve the files, you may need SSH/deploy keys setup
* Set your web server to serve the "web" folder (e.g., 'mukurtu4/web')
* Install Drupal as normal, the Mukurtu profile distribution will automatically be used
