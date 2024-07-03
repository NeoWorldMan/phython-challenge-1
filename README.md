# phython-challenge-1
 Module 2 Challenge
 

 ## Variety Food Truck Order System

This Python script is an order placement system for a food truck. The user can order items from different categories such as Snacks, Meals, Drinks, and Desserts. The script displays the menu, handles user inputs, and keeps track of the order placed by the customer.


### Features

- Display menu categories and items with prices.
- Take orders from the user.
- Handle multiple orders.
- Calculate and display the total price of the order.


### Requirements

- Python 3.10 or higher.


### Usage

1. **Run the script:**

   ```bash
   python menu.py
   
2. Follow the prompts to place an order:

- The script will greet you and ask from whick menu category you would like to order.
- Enter the menu number corresponding to the category you wish to order from.
- Choose an item from the selected category by entering the item number.
- Specify the quantity of the item you wish to order.
- You can continue ordering by answering 'Y' when prompted, or finish your order by answering 'N'.

3. View your order summary and total price:

- Once you have finished ordering, the script will display your complete order with item names, prices, quantitites, and the total price.

Example:

Here's an example iteraction with the script:

Welcome to the variety food truck.
From which menu would you like to order? 
1: Snacks
2: Meals
3: Drinks
4: Dessert
Type menu number: 2
You selected Meals
What Meals item would you like to order?
Item # | Item name                | Price
-------|--------------------------|-------
1      | Burrito                  | $4.49
2      | Teriyaki Chicken         | $9.99
3      | Sushi                    | $7.49
4      | Pad Thai                 | $6.99
5      | Pizza - Cheese           | $8.99
6      | Pizza - Pepperoni        | $10.99
7      | Pizza - Vegetarian       | $9.99
8      | Burger - Chicken         | $7.49
9      | Burger - Beef            | $8.49

Please input menu item selection number: 1
Please enter the desired quantity: 2
Would you like to keep ordering? (Y)es or (N)o N
Thank you for your order
This is what we are preparing for you.

Item name                 | Price  | Quantity
--------------------------|--------|----------
Burrito                   | 4.49   | 2

Total price is: $8.98.

Notes:
- Make sure you are using Python 3.10 or higher to ensure compatibility with the match statement.
- The script includes error handling for invalid inputs such as non-numeric menu selections or quantities.
