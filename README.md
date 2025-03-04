# WHMCS Banner Manager
The Banner Manager allows you to insert notification alerts, images and RAW HTML into 4 areas of WHMCS for your admins and clients to view.

## Supported Page Locations

**Client Area**
* Header
* Footer
* Homepage
* Product Details
* Domain Details
* Checkout
* View Cart

**Admin Area**
* Header
* Footer
* Homepage
* Invoice Controls
* View Ticket Page
* Client Summary Page

## Requirements
- WHMCS 7, 8+
- PHP 7.4, 8.1+

## Installation
Installing this addon module is very straight forward and requires no code changes. Just follow these steps to get up and running:

* Download this Github Repo and unzip it, direct download: https://github.com/hostmedia/whmcs-bannermanager-encoded/archive/refs/heads/main.zip
* Depending on your WHMCS/server installation use the Ioncube version supported, you can find which version you are using by checking your WHMCS Admin->Utilities->System->PHP Info (https://domain.com/whmcs-directory/admin/systemphpinfo.php)
* Upload the contents of the Ioncube version folder to your WHMCS root directory, this will be two folders (assets & modules).
* Once uploaded, navigate to WHMCS admin, addons section to activate the module, when activated, select the 'Configure' option for the module and enter your license key and make sure to select the user groups you wish to have access
* Now everything has been setup, you can click on Addons in the top navigation bar to see the "BannerManager" option. If you do not see this option, double check your user group configuration on the addon module.

## Upgrade
Before uploading the a new version of the Banner Manager, please make sure to take a backup of your WHMCS database.

Upgrading from 1.1.x to 1.2.x
* Backup your WHMCS database as version 1.2.x has database changes that could impact your current module installation.
* Upload the files from the latest release to your WHMCS install directory and overwrite the existing install.
* Navigate to WHMCS admin, addons section and next to this active module, click on 'Configure'.
* There are 2 new fields to complete; 'Upload Directory' which needs to be your absolute path to store uploaded images, we recommend a path outside of your web root. Secondly "Max Image Dimension" for uploads, this is to help lower image sizes if you wish, we recommennd keeping to the default of '1024'.
    
## License Key
To purchase a license key please order at: https://hostmedia.uk/client/store/lab-products/whmcs-banner-manager

Price: £4.99 per year (ex VAT)

## Ioncube Loaders
We have provided the WHMCS Banner Manager software available with two IonCube Loaders (12, 13 and 14).

| Ioncube Version  | Module PHP Compatibility |
| ------------- | ------------- |
| 12  | 7.4 - 8.1 |
| 13  | 7.4 - 8.2 |
| 14  | 7.4 - 8.3 |

Download Loader: https://www.ioncube.com/loaders.php

## Support
If you have any issues please open a ticket to our development team at: https://hostmedia.uk/client/submitticket.php?step=2&deptid=21
