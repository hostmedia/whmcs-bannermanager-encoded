# WHMCS Banner Manager
The Banner Manager allows you to insert notification alerts, images, WYSIWYG generated content and RAW HTML into your WHMCS pages for your admins and clients to view.

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

**Custom Tag**
* Custom Client Area Template Tag

## Requirements
- WHMCS 7, 8+
- PHP Recommended 8.1+
- Ioncube PHP Encoded Support 7.4+

## Installation
Installing this addon module is very straight forward and requires no code changes. Just follow these steps to get up and running:

* Download this Github Repo and unzip it, direct download: https://github.com/hostmedia/whmcs-bannermanager-encoded/archive/refs/heads/main.zip
* Upload the contents to your WHMCS root directory.
* Once uploaded, navigate to WHMCS admin, addons section to activate the module, when activated, select the 'Configure' option for the module and enter your license key and make sure to select the user groups you wish to have access.
* Now everything has been setup, you can click on Addons in the top navigation bar to see the "BannerManager" option. If you do not see this option, double check your user group configuration on the addon module.

## Upgrade
Before uploading the a new version of the Banner Manager, please make sure to take a backup of your WHMCS database.

Upgrading from 1.1.x to 1.2.x
* Backup your WHMCS database as version 1.2.x has database changes that could impact your current module installation.
* Upload the files from the latest release to your WHMCS install directory and overwrite the existing install.
* Navigate to WHMCS admin, addons section and next to this active module, click on 'Configure'.
* There are 2 new fields to complete; 'Upload Directory' which needs to be your absolute path to store uploaded images, we recommend a path outside of your web root. Secondly "Max Image Dimension" for uploads, this is to help lower image sizes if you wish, we recommennd keeping to the default of '1024'.

Upgrading from <1.2.x to 1.3.1
* There are no database changes but as always we recommend backing up your data before upgrading.
* Version 1.3.x and above will now require PHP 8.1 as the minimum supported PHP version.

Upgrading from <1.3.1 to 1.4.0
* Backup your WHMCS database as version 1.3.2 onwards has database changes that could impact your current module installation.
* Follow the standard documented process for upgrading

Upgrading from 1.4.0 to 1.4.1
* There are no database changes but as always we recommend backing up your data before upgrading.
* Version 1.4.1 and above now recommends PHP 8.1 as the minimum supported PHP version, but encoding will support PHP 7.4.

## License Key
To purchase a license key please order at: https://portal.hostmedia.uk/store/software/whmcs-banner-manager

## Ioncube Loaders
The WHMCS Banner Manager is encoded using the latest Ioncube loader, this does support backward compatibility but recommend always using the lastest Ioncube loader

Download Loader: https://www.ioncube.com/loaders.php

## Support
If you have any issues please open a ticket to our development team at: https://portal.hostmedia.uk/submitticket.php?step=2&deptid=21
