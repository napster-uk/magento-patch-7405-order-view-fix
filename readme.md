* Author: Sofiane Khelfaoui
* Email: Sofianek94@gmail.com
* Description: Module to fix the magento patch 7405 admin order view issue.
* Issue: If your server PHP version is < 5.4 incompatibility so the issue will raise. otherwise ignore this module.
* Module Tested in versions: Magento Version 1.7.2.

Please make a full backup of your website before using this module, i don't take any responsibility for anything happens to your website after installing this module.

Installation:

1- Copy the module folder Sofiane inside your app->code->local.

2- Add the file Sofiane_Order.xml from etc/modules folder to your etc/modules folder.



Uninstall:

to uninstall the module just navigate to app->etc->modules find Sofiane_Order.xml open the fle and change:

this <br>
active **true** /active

to be <br>

 active **false** /active

 Clear the cache after that and you are done.

 Many Thanks for your suport.

 Sofiane Khelfaoui
