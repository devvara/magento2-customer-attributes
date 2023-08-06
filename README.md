## Magento 2 Customer Attributes Module for v2.4.*

This module has been modified to work with Magento 2.4.* versions, based on the magento2-customer-attributes module.

#### Based on the Original Module

[laptc/magento2-customer-attributes on GitHub](https://github.com/laptc/magento2-customer-attributes)

#### Updates

- **Error fixes for Magento 2.4.***
- **Menu Location Adjustments** (STORES > Attributes)
- **Compatibility with Magento 2.4.**: This version of the module has been tested and patched for Magento 2.4.*

#### Installation

1. Clone or download this repository to your Magento root directory.
2. Navigate to your Magento root directory via terminal and run:

   ```bash
   php bin/magento module:enable Mvn_Cam 
   php bin/magento setup:upgrade 
   php bin/magento cache:clean

#### License

This module inherits the license from the original module. Please check the original module's license for more details.