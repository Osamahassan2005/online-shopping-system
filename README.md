Report: CLI-Based Online Shopping System

1. Introduction

The CLI-Based Online Shopping System is a Python-based application that enables users to perform online shopping operations through a command-line interface. It includes Admin and Customer functionalities, allowing product management, cart operations, and order placement.


---

2. System Features

Admin Features:

1. View Admin Details – Displays admin information.


2. Add Products – Admin can add new products to the inventory.


3. Update Stock – Modify the quantity of existing products.


4. Remove Products – Delete products from the inventory.


5. View Products – Display all available products.


Customer Features:

1. View Available Products – Displays all items in stock.


2. Add Products to Cart – Customers can add items to their shopping cart.


3. View and Update Cart – Review and modify cart items.


4. Place Order – Checkout and confirm order placement.



---

3. Implementation Details

The system is structured as follows:

online-shopping-system/
│── main.py                      # Main entry point of the application
│── data/
│   ├── admins.csv                # Admin data
│   ├── order_history.csv         # Order history data
│   ├── products.csv              # Product list
│── models/
│   ├── cart.py                   # Shopping cart model
│   ├── product.py                # Product model
│── users/
│   ├── admin.py                  # Admin functionalities
│   ├── customer.py               # Customer functionalities
│   ├── user.py                    # User base class

---

4. Sample Execution & Output

Admin Menu:

Admin Options:
1) View Details
2) Add Product
3) Update Stock
4) Remove Product
5) View Products
6) Logout

Enter your choice: 5

Output:

Available Products:
1. Laptop - $1000 (Stock: 5)
2. Smartphone - $500 (Stock: 10)

Adding a Product:

Enter Product name: Headphones
Enter Product price: 100
Enter Product stock: 15

Output:

Headphones added successfully!

---

Customer Menu:

Hello, Customer!
-----------------------------
1) View Products
2) Add to Cart
3) View Cart
4) Checkout
5) Exit

Enter your choice: 2

Adding a Product to Cart:

Enter Product name: Laptop
Enter Quantity: 1

Output:

Laptop added to cart!

Viewing Cart:

1. Laptop - $1000 (Quantity: 1)
Total Amount: $1000

Placing Order:

Proceed to checkout? (yes/no): yes

Output:

Order placed successfully!

---

5. Data Storage

Products are stored in data/products.csv

Order history is stored in data/order_history.csv

Admin credentials are stored in data/admins.csv

---

6. Conclusion

The CLI-Based Online Shopping System efficiently allows admins to manage products and customers to shop conveniently. The system follows an interactive command-line interface to provide a smooth shopping experience.
