# ExampleModuleSkeleton module for Magento 2
This module is only a simple skeleton for further modifications.

## Installation
To install use the following composer command:

    composer require yireo-training/magento2-example-module-skeleton:dev-master

Next enable the module:

    bin/magento module:enable Yireo_ExampleModuleSkeleton
    bin/magento setup:upgrade

And flush the cache:

    bin/magento cache:clean

# Proof of concept
Run `bin/magento module:status` to see if the module has been installed.
