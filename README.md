# Bamazon App
This is a CLI application which functions like an online storefront. With two different features, the user can act as a ‘customer’, where they can view all available items and make purchases; or ‘manager’, where they will be able to view available inventory for all products, search for which items are low inventory, add inventory to any available products, and add entirely new products to the store options.

## Getting Started
Since this app requires MySQL, you will need to make sure that package is installed on your computer first. Windows users can use MySQL Workbench and Mac users can use Sequel Pro.
* Windows Installation:
[click here](https://dev.mysql.com/downloads/installer/) and follow the instructions
* Mac Installation:

    brew install mysql

Once installed, you can use the schema.sql file to create your database in MySQL. You’ll need to set this up in order for any future code to work properly.


This is a Node-based application designed to run in your terminal. You will need the node library installed as well as the following npm packages in order to get the app features to work in Node.js:

*Node.js library installation
  -[Windows link](https://nodejs.org/en/)

  -Mac:

    brew install node


    npm install inquirer
    npm install mysql
    npm install cli-table


### Customer View
From the customer view in the terminal a user will be able to do the following:

1. View a list of current products for sale:

![products image](/images/store_front.PNG)

2. Choose a product to purchase and the amount they desire:

If there is enough product in stock to complete the user’s order, the order will go through and display the total cost to the customer.

![product bought](/images/product_bought.gif)

If there is not enough of the product, the store will bounce back with a message explaining there is not enough.

![not enough inventory](/images/not_enough.gif.gif)

From there, it will prompt the user if they wish to continue shopping or finish, at which point it will return them to the opening prompt or end the application.

![keep shopping](/images/keep_shopping.PNG)

### Manager View
As a manager, the user will first be prompted with a list of options to choose from, that will then allow the user to complete different actions within the store:
(img screenshot)
 
*View Products:

![view products](/images/view_products.PNG)

*Low Inventory:

![low inventory](/images/low_inventory.PNG)

*Add to Inventory:

![add to inventory](/images/add_stock.gif)

*Add New Product:

![new product](/images/new_product.gif)


## Author
Carmen Stockberger - [https://github.com/carmenanne](https://github.com/carmenanne)

Cheers!
