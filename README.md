# BAMAZON

### The Ultimate Shopping Experience!

The BAMAZON experience begins with an initial greeting welcoming the customer, asking if they would like to continue shopping or not. If yes, the user is presented with a list of the most popular items in stock. Each line item in the table contains an id number as well as the corresponding department, price, and remaining stock quantity.  



If the customer would like to place an order, they are prompted (via Inquirer Node Package) to enter the item Id, followed by a separate prompt asking how many they would like to order. If there is adequate stock to fulfill a request, the order is processed and a confirmation message is displayed. The program will update the database and stock levels will be adjusted. If their order exceeds the number of items in stock, a message indicating such will be returned to the customer.

When an order is completed, summary confirmation will be returned to the customer in object form with the product name, department, price, quantity and total amount (along with a 'thank you for shopping with bamazon' message).

ORDER SUMMARY:
Item: Magnification Mirror
Department: Beauty
Price: 29.99
Quantity: 2
Total: 59.98
THANK YOU FOR SHOPPING AT BAMAZON! You will receive a tracking number shortly!

### Building BAMAZON

To build this Node.js command line application, NPM is initialized and Inquirer and mysql NPM packages are installed in the root directory. The Inquirer module is required in order to prompt the customer.

* Inquirer

The inventory feauture is built using mysql database with a products table containing each item, their correpsonding ID, department, price and stock level. 

* mysql 


## Functionality for the Bamazon customer experience

#### example of prompt with customer input;

![](images/bam_best_sweater.gif)


#### when out-of-stock happens;

![](images/no-stock.png)


#### when customer decides not to stay

![](images/not-staying.gif)








