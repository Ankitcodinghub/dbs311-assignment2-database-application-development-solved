# dbs311-assignment2-database-application-development-solved
**TO GET THIS SOLUTION VISIT:** [DBS311 Assignment2-Database Application Development Solved](https://www.ankitcodinghub.com/product/dbs311-assignment2-database-application-development-solved/)


---

📩 **If you need this solution or have special requests:** **Email:** ankitcoding@gmail.com  
📱 **WhatsApp:** +1 419 877 7882  
📄 **Get a quote instantly using this form:** [Ask Homework Questions](https://www.ankitcodinghub.com/services/ask-homework-questions/)

*We deliver fast, professional, and affordable academic help.*

---

<h2>Description</h2>



<div class="kk-star-ratings kksr-auto kksr-align-center kksr-valign-top" data-payload="{&quot;align&quot;:&quot;center&quot;,&quot;id&quot;:&quot;61785&quot;,&quot;slug&quot;:&quot;default&quot;,&quot;valign&quot;:&quot;top&quot;,&quot;ignore&quot;:&quot;&quot;,&quot;reference&quot;:&quot;auto&quot;,&quot;class&quot;:&quot;&quot;,&quot;count&quot;:&quot;3&quot;,&quot;legendonly&quot;:&quot;&quot;,&quot;readonly&quot;:&quot;&quot;,&quot;score&quot;:&quot;5&quot;,&quot;starsonly&quot;:&quot;&quot;,&quot;best&quot;:&quot;5&quot;,&quot;gap&quot;:&quot;4&quot;,&quot;greet&quot;:&quot;Rate this product&quot;,&quot;legend&quot;:&quot;5\/5 - (3 votes)&quot;,&quot;size&quot;:&quot;24&quot;,&quot;title&quot;:&quot;DBS311 Assignment2-Database Application Development Solved&quot;,&quot;width&quot;:&quot;138&quot;,&quot;_legend&quot;:&quot;{score}\/{best} - ({count} {votes})&quot;,&quot;font_factor&quot;:&quot;1.25&quot;}">

<div class="kksr-stars">

<div class="kksr-stars-inactive">
            <div class="kksr-star" data-star="1" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="2" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="3" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="4" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" data-star="5" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>

<div class="kksr-stars-active" style="width: 138px;">
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
            <div class="kksr-star" style="padding-right: 4px">


<div class="kksr-icon" style="width: 24px; height: 24px;"></div>
        </div>
    </div>
</div>


<div class="kksr-legend" style="font-size: 19.2px;">
            5/5 - (3 votes)    </div>
    </div>
<strong>Objective:</strong>

In this assignment, you create a simple Retail application using the C++ programming language and Oracle (PL/SQL). This assignment helps students learn a basic understanding of application development using C++ programming and an Oracle database using PL/SQL.

<strong>Submission:</strong>

<strong><em>Your submission will be a single text-based .cpp file including your C++ program for the Database Application assignment.</em></strong>

A2_Lastname.cpp

Your submission needs to be commented.

<strong>Other notes:</strong>

This is a group assignment. Not an individual assignment. You are to form your own groups.

The submission is

1) The CPP file as mentioned above

2) A simple video showing you testing out the program to prove it works as required.

(You should pre-decide how you are going to demonstrate the program working so that you do not keep repeating errors. The video does not need to be a work of art, but a simple screen of your group testing the assignment)

3) this assignment is a lot of work, so please do not leave it to the last minute.

<strong>Instruction:</strong>

In this assignment, we use the same database that you have been using for the labs and the assignment 1.

<strong><u>Note</u></strong>: For each query in your assignment, make sure you handle the errors and display the proper message including the error code and the error message.

try{

…

}

catch (SQLException&amp; sqlExcp) {

cout &lt;&lt; sqlExcp.getErrorCode() &lt;&lt; “: ” &lt;&lt; sqlExcp.getMessage();

}

&nbsp;

Declare the following structure before the <strong><em>main()</em></strong> function:

struct ShoppingCart {

int product_id;

double price;

int quantity;

};

&nbsp;

<strong><em>Connecting to an Oracle database from a C++ Program</em></strong>

&nbsp;

In your function <strong><em>main()</em></strong>, create a connection to your database.

&nbsp;

First, declare the environment and the connection variables.

Environment* env = nullptr;

Connection* conn = nullptr;

&nbsp;

Define and initialize the variable to store the username, password, and the host address.

string user = “username”;

string pass = “password”;

string constr = “myoracle12c.senecacollege.ca:1521/oracle12c”;

&nbsp;

Use the same Oracle username and password that you use for your labs and assignments.

Create the environment and the connection. Make sure you handle any errors may be thrown as you program is executed.

&nbsp;

env = Environment::createEnvironment(Environment::DEFAULT);

conn = env-&gt;createConnection(user, pass, constr);

&nbsp;

Remember to terminate and close the connection and the environment, when your program terminates.

env-&gt;terminateConnection(conn);

Environment::terminateEnvironment(env);

&nbsp;

After executing the statements make sure you terminate the statement.

conn-&gt;terminateStatement(stmt);

&nbsp;

You will implement the following Oracle stored procedures and C++ functions:

<strong><em>&nbsp;</em></strong>

<strong><em>Stored Procedures</em></strong>

&nbsp;

<em>find_customer (customer_id IN NUMBER, found OUT NUMBER);</em>

&nbsp;

This procedure has an input parameter to receive the customer ID and an output parameter named found.

This procedure looks for the given customer ID in the database. If the customer exists, it sets the variable <em>found</em> to 1. Otherwise, the <em>found</em> variable is set to 0.

To check if your query in the <strong><em>find_customer()</em></strong> procedure returns a row, you can check the no_data_found exception in the EXCEPTION block.

EXCEPTION

WHEN no_data_found THEN

found := 0;

&nbsp;

<em>find_product (product_id IN NUMBER, price OUT products.prod_sell%TYPE);</em>

&nbsp;

This procedure has an input parameter to receive the product ID and an output parameter named price.

This procedure looks for the given product ID in the database. If the product exists, it stores the product’s list_price (prod_sell) in the variable <em>price</em>. Otherwise, the <em>price</em> variable is set to 0.

&nbsp;

EXCEPTION

WHEN no_data_found THEN

price := 0;

&nbsp;

<em>add_order (customer_id IN NUMBER, new_order_id OUT NUMBER)</em>

&nbsp;

This procedure has an input parameter to receive the customer ID and an output parameter named new_order_id.

To add a new order for the given customer ID, you need to generate the new order Id. To calculate the new order Id, find the maximum order ID in the orders table and increase it by 1.

This procedure inserts the following values in the ORDERS table:

new_order_id

customer_id (input parameter)

‘Shipped’ (The value for the order status) (C for closed and shipped, O for open order not shipped yet)

36 (The salesperson ID)

sysdate (order date which is the current date)

&nbsp;

<em>&nbsp;</em>

<em>&nbsp;</em>

<em>add_orderline (orderId IN orderlines.order_no%type,

itemId IN orderlines.line_no%type,

productId IN orderlines.prod_no%type,

quantity IN orderlines.qty%type,

price IN orderlines.price%type)</em>

This procedure has five IN parameters. It stores the values of these parameters to the table ORDERLINES

<strong><em>&nbsp;</em></strong>

<strong><em>C++ Functions</em></strong>

<strong><em>&nbsp;</em></strong>

<em>int mainMenu();</em>

The <strong><em>mainMenu()</em></strong> function returns an integer value which is the selected option by the user from the menu. This function displays the following menu options:

&nbsp;

<ul>
<li>Login</li>
<li>Exit</li>
</ul>
&nbsp;

Prompt the user to choose an option. If the user enters the wrong value, ask the user to enter an option again until the user enters a valid option.

&nbsp;

See the following example:&nbsp;&nbsp; The yellow XXXX should be one of your groups last name

&nbsp;

*************Main Menu by XXXXXXXXX ********************

1)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Login

0)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Exit

Enter an option (0-1): 5

*************Main Menu by XXXXXXXXX ********************

1)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Login

0)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Exit

You entered a wrong value. Enter an option (0-1):

&nbsp;

If the user chooses option 1, ask the user to enter customer ID to login. To see if the customer with the entered ID exists, call the Oracle stored procedure <strong><em>find_customer()</em></strong>. IF the value of the output parameter in the procedure is 1, let the customer to continue. If the value of the output parameter found is 0, call the <strong><em>mainMenu()</em></strong> functions again and ask the customer to login again. Continue this process until the user chooses the option 0 to exit or enters a valid customer ID.

&nbsp;

<em>int customerLogin(Connection* conn, int customerId);</em>

&nbsp;

Before you call this function, prompt the user to enter the customer ID.

Call this function in the <strong><em>main()</em></strong> function if the user chooses the login option from the main menu. This function receives an integer value as a customer ID and checks if the customer does exist in the database. This function returns 1 if the customer exists. If the customer does not exist, this function returns 0 and the main menu is displayed.

To validate the customer ID call the <strong><em>find_customer()</em></strong> stored procedure in this function.

&nbsp;

&nbsp;

See the following example:

&nbsp;

*************Main Menu by XXXXXXXXX ********************

1)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Login

0)&nbsp;&nbsp;&nbsp;&nbsp; &nbsp;Exit

Enter an option (0-1): 1

Enter the customer ID: 1000

The customer does not exist.

*************Main Menu by XXXXXXXXX ********************

1)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Login

0)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Exit

Enter an option (0-1): 1

Enter the customer ID: 44

————– Add Products to Cart ————–

Enter the product ID:

&nbsp;

<em>int addToCart(Connection* conn, struct ShoppingCart cart[]);</em>

<em>&nbsp;</em>

If the customerLogin() functions return 1 (The customer ID exists), call this function.

This function receives an OCCI pointer (a reference variable to an Oracle database) and an array of type ShoppingCart.

&nbsp;

The customer can purchase up to five items in one order.

Write a loop to prompt the user to enter product IDs for the maximum of five products.

&nbsp;

When the user enters the product ID in the <em>addToCart()</em> function, calls the findProduct() function (see function below for more details) to check if the product ID exists. IF the product exists, the function findProduct() returns the product’s price. Display the product’s price to the user and ask the user to enter the quantity.

&nbsp;

If the <strong><em>findProduct()</em></strong> function returns 0 (The product ID does not exist), display a proper message and let the user enter the product ID again.

&nbsp;

Continue with

“Enter 1 to add more products or 0 to checkout: ”

&nbsp;

If the user chooses 1, ask the user to enter the next product ID. Otherwise, go to the next step to checkout. If the user enters 0, the function <strong><em>addToCart()</em></strong>, returns the number of products (items) entered by the user.

&nbsp;

For each product ID entered by the customer call the function <strong><em>findProduct()</em></strong> to see if the product ID exists.

&nbsp;

See the following example:

&nbsp;

————– Add Products to Cart ————–

Enter the product ID: 1000

The product does not exist. Try again…

Enter the product ID: 900

The product does not exist. Try again…

Enter the product ID: 112

Product Price: 808.92

Enter the product Quantity: 3

Enter 1 to add more products or 0 to checkout: 1

Enter the product ID: 115

Product Price: 699.99

Enter the product Quantity: 2

Enter 1 to add more products or 0 to checkout: 0

&nbsp;

<em>double findProduct(Connection* conn, int product_id);</em>

<em>&nbsp;</em>

This function receives an OCCI pointer (a reference variable to an Oracle database) and an integer value as the product ID.

&nbsp;

When the user enters the product ID in the <strong><em>addToCart()</em></strong> function, the function <strong><em>findProduct()</em></strong> is called.

&nbsp;

This function calls the <strong><em>find_product()</em></strong> Oracle stored procedure. The procedure receives the product ID and returns the price. If the price is 0, the product ID is not valid (does not exist). If the price is a non-zero value, it means the product ID is valid.

<em>&nbsp;</em>

<em>void displayProducts(struct ShoppingCart cart[], int productCount);</em>

<em>&nbsp;</em>

This function receives an array of type ShoppingCart and the number of ordered items (products). It display the product ID, price, and quantity for products stored in the cart array.

&nbsp;

Call this function after the function <strong><em>AddToCart()</em></strong> to display the products added by the user to the shopping cart.

&nbsp;

——- Ordered Products ———

—Item 1

Product ID: 112

Price: 808.92

Quantity: 3

—Item 2

Product ID: 115

Price: 699.99

Quantity: 2

———————————-

Total: 3826.74

&nbsp;

After displaying the products’ information (product ID, price, and quantity), display the total order amount. To calculate the total order amount, first multiply the quantity and the price to calculate the total amount for each product. Next, sum up products’ total amounts to calculate the total order amount.

&nbsp;

<em>int checkout(Connection *conn, struct ShoppingCart cart[], int customerId, int productCount);</em>

<strong><em>&nbsp;</em></strong>

Call this function after the function <strong><em>displayProduct()</em></strong>.

This function receives an OCCI pointer (a reference variable to an Oracle database), an array of type ShoppingCart, an integer value as the customer ID, and an integer value as the number of ordered items (products).

&nbsp;

First, display the following message:

“Would you like to checkout? (Y/y or N/n) ”

If the user enters any values except “Y/y” and “N/n”, display a proper message and ask the user to enter the value again.

“Wrong input. Try again…”

&nbsp;

See the following example:

&nbsp;

*************Main Menu by XXXXXXXXX ********************

1)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Login

0)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Exit

Enter an option (0-1): 1

Enter the customer ID: 4

————– Add Products to Cart ————–

Enter the product ID: 112

Product Price: 808.92

Enter the product Quantity: 3

Enter 1 to add more products or 0 to checkout: 0

——- Ordered Products ———

—Item 1

Product ID: 112

Price: 808.92

Quantity: 3

———————————-

Total: 2426.76

Would you like to checkout? (Y/y or N/n) t

Wrong input. Try again…

Would you like to checkout? (Y/y or N/n) 0

Wrong input. Try again…

Would you like to checkout? (Y/y or N/n) 1

Wrong input. Try again…

Would you like to checkout? (Y/y or N/n) y

The order is successfully completed.

*************Main Menu by XXXXXXXXX ********************

1)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Login

0)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Exit

Enter an option (0-1): 0

Good bye!…

&nbsp;

If the user enters “N/n”, the function <strong><em>checkout()</em></strong> terminates and returns 0.

&nbsp;

If the user enters “Y/y”, the Oracle stored procedure <strong><em>add_order()</em></strong> is called. This procedure will add a row in the orders table with a new order ID (See the definition of the <strong><em>add_order()</em></strong> procedure.

This stored procedure returns an order ID, which will be used to store ordered items in the table orders.

&nbsp;

The line_no for the first product in the array is 1, for the second product is 2, and …

For all products in the array cart (<em>productCount</em> is the number of products stored in the array <em>cart</em>), call the stored procedure <strong><em>add_orderlines()</em></strong> and pass the corresponding values to this stored procedure.

&nbsp;

Sample execution:

&nbsp;

*************Main Menu by XXXXXXXXX ********************

1)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Login

0)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Exit

Enter an option (0-1): 5

*************Main Menu by XXXXXXXXX ********************

1)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Login

0)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Exit

You entered a wrong value. Enter an option (0-1): 1

Enter the customer ID: 1000

The customer does not exist.

*************Main Menu by XXXXXXXXX ********************

1)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Login

0)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Exit

Enter an option (0-1): 44

*************Main Menu by XXXXXXXXX ********************

1)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Login

0)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Exit

You entered a wrong value. Enter an option (0-1): 1

Enter the customer ID: 44

————– Add Products to Cart ————–

Enter the product ID: 112

Product Price: 808.92

Enter the product Quantity: 2

Enter 1 to add more products or 0 to checkout: 1

Enter the product ID: 115

Product Price: 699.99

Enter the product Quantity: 3

Enter 1 to add more products or 0 to checkout: 0

——- Ordered Products ———

—Item 1

Product ID: 112

Price: 808.92

Quantity: 2

—Item 2

Product ID: 115

Price: 699.99

Quantity: 3

———————————-

Total: 3717.81

Would you like to checkout? (Y/y or N/n) y

The order is successfully completed.

*************Main Menu by XXXXXXXXX ********************

1)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Login

0)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Exit

Enter an option (0-1): 1

Enter the customer ID: 44

————– Add Products to Cart ————–

Enter the product ID: 110

Product Price: 3192.97

Enter the product Quantity: 2

Enter 1 to add more products or 0 to checkout: 1

Enter the product ID: 116

Product Price: 731.99

Enter the product Quantity: 1

Enter 1 to add more products or 0 to checkout: 1

Enter the product ID: 117

Product Price: 695.99

Enter the product Quantity: 3

Enter 1 to add more products or 0 to checkout: 0

——- Ordered Products ———

—Item 1

Product ID: 110

Price: 3192.97

Quantity: 2

—Item 2

Product ID: 116

Price: 731.99

Quantity: 1

—Item 3

Product ID: 117

Price: 695.99

Quantity: 3

———————————-

Total: 9205.9

Would you like to checkout? (Y/y or N/n) n

The order is cancelled.

*************Main Menu by XXXXXXXXX ********************

1)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Login

0)&nbsp;&nbsp;&nbsp;&nbsp;&nbsp; Exit

Enter an option (0-1): 0

Good bye!…

&nbsp;
