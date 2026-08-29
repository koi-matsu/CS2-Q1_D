# PROJECT TITLE: Smart Grocery and Budget Calculator with Quantity and Price Sorting 

# PROJECT DESCRIPTION
  This is a Python program designed to help users organize their grocery shopping and manage their expenses. It allows users to add grocery items along with their prices and quantities, calculate the total cost of each item and the entire grocery list, and sort items from the highest to lowest price. The program uses lists, conditions, loops, and the math library to efficiently manage and calculate grocery information.

# PROBLEM
  People often forget the grocery items they need, have difficulty calculating the total cost when buying multiple quantities, and may have difficulty identifying which items are the most expensive. This can make grocery shopping less organized and make it harder to manage a budget.

# FEATURES
- Add Item: Allows users to enter the grocery item name, price, and quantity.
- View Grocery List: Displays all added items, their prices, quantities, and total prices.
- Compute Total Cost: Calculates the overall cost of all grocery items.
- Sort Items by Price: Arranges grocery items from the highest to the lowest price.
- Menu System: Lets users choose different actions through a simple menu.
- Exit: Allows users to end the program.
- Automatic calculations: Calculates each item's total price using **price x quantity**
- Budget Tracking: Helps users see how much they are spending on their groceries.

# INPUTS NEEDED
- Item name ("string")
- Item price ("float")
- Quantity ("integer")
- Menu choice ("integer")

# PROCESSES
6The program will:
1. Allow the user to add grocery items.
2. Store item names, prices, and quantities in separate Python lists.
3. Calculate the total price of each item by multiplying its price by its quantity.
4. Calculate the overall cost of all grocery items.
5. Sort the grocery items from highest to lowest based on price.
6. Use Python's "math" library for mathematical operations.
7. Display the grocery information in the Python console.

# OUTPUTS
The program will display:
- Grocery item name
- Item price
- Quantity
- Total price for each item
- Overall total cost
- Grocery items sorted from highest to lowest price

# PROGRAM FLOW
1. Start the program.
2. Display the main menu.
3. The user selects an option.
4. If the user chooses Add Item:
   - Enter the item name.
   - Enter the item price.
   - Enter the quantity.
   - Store the information in the appropriate lists.
5. If the user chooses View Grocery List:
   - Display all stored grocery items.
   - Calculate and display the total price for each item.
6. If the user chooses Compute Total Cost:
   - Multiply the price by the quantity of each item.
   - Add all item totals.
   - Display the overall total cost.
7. If the user chooses Sort Items by Price:
   - Arrange the items from highest to lowest price.
   - Display the sorted grocery list.
8. If the user chooses Exit:
   - End the program.
9. Repeat the process until the user chooses Exit.

# EXAMPLE OUTPUT
========================================
       SMART GROCERY LIST & BUDGET
========================================

1. Add Item
2. View Grocery List
3. Compute Total Cost
4. Sort Items by Price
5. Exit

Enter your choice: 1

Enter item name: Rice
Enter item price: 55
Enter quantity: 2

Item added successfully!

Enter your choice: 1

Enter item name: Milk
Enter item price: 90
Enter quantity: 1

Item added successfully!

Enter your choice: 1

Enter item name: Chicken
Enter item price: 180
Enter quantity: 2

Item added successfully!

Enter your choice: 2

---------- GROCERY LIST ----------
Item        Price     Quantity     Total
Rice        ₱55.00       2        ₱110.00
Milk        ₱90.00       1         ₱90.00
Chicken     ₱180.00      2        ₱360.00

Enter your choice: 3

---------- TOTAL COST ----------
Overall Total: ₱560.00

Enter your choice: 4

------ SORTED BY HIGHEST PRICE ------
Chicken     ₱180.00
Milk         ₱90.00
Rice         ₱55.00

Enter your choice: 5

Thank you for using Smart Grocery List!
Program ended.

# CONTRIBUTORS
* Student 1: Gia Nicole P. Villafuerte (Menu system, user interface, and input validation)
* Student 2: Kadesh Chantelle G. Samson (grocery item storage, quantity and price calculations)
* Student 3: Kloie O. Inabangan (sorting, total cost feature, testing and debugging)



  
