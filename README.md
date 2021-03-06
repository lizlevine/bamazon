# Bamazon: the ultimate shopping experience! 

The BAMAZON experience begins with an initial greeting welcoming the user into the store and prompting them to answer (Y/N), if they would like to continue shopping. If yes, the user is presented with a list of the most popular items in stock. Each line-item in the table contains an id number as well as it's corresponding department, price, and the remaining stock level.

If the customer would like to place an order, they are prompted (via Inquirer Node Package) to enter the item id and number of units.

If there is adequate stock to fulfill a request, the order is processed and a confirmation message is displayed. The program will update the database and stock levels will be adjusted. If their order exceeds the number of items in stock, a message indicating such will be returned to the customer.

When an order is completed, a summary confirmation will be returned to the customer as an object:

![](images/customer-receipt.png)

## Building Bamazon: Required tools & tech 

To build this NODE.js command line application, NPM is initialized and Inquirer and mysql NPM packages are installed in the root directory. The Inquirer module is required in order to prompt the customer.

The inventory feauture is built using MySQL database with a products table containing each item, their correpsonding id, department, price and stock level.

- Inquirer: (https://www.npmjs.com/package/inquirer)
- MySQL: (https://www.npmjs.com/package/mysql)

## Functionality for the Bamazon customer experience 

### Example of prompt with customer input; 

![](images/bam_best_sweater.gif)

### When the order exceeds stock levels; 

![](images/no-stock.png)

### When the customer decides not to stay;

![](images/not-staying.png)

### Products table from MySQL database;

![](images/MySQL_db_table.png)