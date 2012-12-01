Featured Products 2.0
====================================

(Revamped version for new Magento CE & EE : for Magento CE lower that 1.6 and EE lower that 1.11, please use older releases.)

This extension gives your Magento ability for easy management of featured products. Frontend features include separate interface for listing of all featured products and a block usage for easy placement to the interfaces of your choice.

Features:
-------
Frontend:

+ **Featured Products Interface** where you can see the list of all featured products and use the options like Sort by, Show X number of products and View type choice.
You can view featured products page on url: www.yourstore.com/featured-products/

+ **Featured Products Block** gives you the ability to place the block to the interface or page of your choice. It is mostly used to display featured products o the home page.
Example: put it in Home page content {{block type="featuredproducts/listing"}}

Backend:

+ **Easy Management of Featured products via separate interface.** You do not have to edit every single product and set it to be featured. You will get the special interface where you will be able to choose the products you want to feature from the list.
Go to admin menu and click on: Catalog > Featured Products

+ **Configuration Options** You will be able to choose layout for Featured product lising interface, use SEO features, Choose the number of products in the block and choose default sort order.

Installation:
-------

+ Make a backup of both files and database
+ If you're upgrading from older version, please uninstall old version (remove old files from app/code/community/Inchoo/FeaturedProducts, app/design/frontend/default/default/template/inchoo, app/design/frontend/default/default/layout/inchoofeaturedproducts.xml and skin/adminhtml/default/default/images/inchoo)
+ Magento Connect: Login to your magentocommerce.com account, copy/paste extension key, enter it to your Magento Connect Manager, and install
+ If you use custom theme you'll need to copy template and layout files from "app/design/frontend/defailt/default" to    "app/design/frontend/your_package/your/theme" in order to see anything on frontend
+ Clear Magento Cache
+ Log out of admin, and log in again
+ If you use flat categorys and flat products tables, disable both of them, clear cache
+ Enable Catalog Products flat first and save it
+ Enable Catalog Categoryes flat and save them

Changelog:
-------

**Version 2.0.0**

Authors
-------

**Darko Goles (Inchoo)**

+ http://inchoo.net