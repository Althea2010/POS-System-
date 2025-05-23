# POS-System-
The POS System is a python-based program designed to manage product transactions, inventory management and customer purchase.  
Authors: Demetrio Burton and Althea Downer
Date Created: April 6, 2025
Course: ITT103 Programming Technique
GitHub Public URL to Code:https://github.com/Althea2010/POS-System-/blob/main/Burton.Downer_POS_Program_ITT103_SP2025.py

https://github.com/DemetrioRB/crispy-adventure/blob/main/Burton.Downer_POS_Program_ITT103_SP2025.py


PURPOSE:
The Best Buy Retail Store POS System is a user-friendly, Python-based Point-of-Sale (POS) solution designed to streamline sales transactions efficiently. Its primary goal is to simplify inventory management, allowing users to easily add and remove products from the cart while keeping stock levels updated. The system also processes payments by calculating the final purchase total, including applicable taxes and discounts, and automatically generates receipts for completed transactions to ensure a smooth checkout experience.

To maintain control and security, removing items from the cart requires administrator-level privileges, preventing unauthorized changes during transactions. Additionally, user switching is supported both from the main menu and during a transaction, allowing seamless access for different users without disrupting the cart’s current state. With these features, along with reliable stock tracking and the flexibility to manage product changes, this POS system provides an effective and secure solution for managing small retail operations


FEATURES:
•	User Authentications: 
1.	The program includes a secure login authentication system that allows the user to make up to three attempts.
2.	Removing items from the cart requires administrator level privileges
3.	User switching is possible from the main menu and during a transaction to remove items while cart maintains its state (empty/full).

•	Inventory Management: 
1.	The system keeps track of product details such as product ID, name of items, price, and available stock. 
2.	It allows users to view available products through various selection options and automatically updates stock levels when items are added to the cart. 

•	Product Search: 
1.	Allow the user to search products by name or category.

•	Cart Operations: 
1.	This functionality allows the user to add multiple items to the cart. remove products entirely or adjust quantities if needed. 
2.	The system also calculates the total cost, incorporating applicable discounts and taxes for an accurate final amount. 

•	Payment Processing: 
1.	The system accepts payments and calculates change while ensuring sufficient funds are provided. If the payment isn’t enough, it alerts the user and offers the option to remove items to match the available funds. 
2.	Once the transaction is completed, a receipt is generated, listing all purchased items, any discounts applied, total charges, and tax.

•	Transaction Handling: 
1.	The system allows cashiers to process multiple transactions seamlessly within a single session. 
2.	It also supports voiding/removing transactions, when necessary, automatically restoring stock to inventory. 
3.	 It helps manage inventory efficiently by detecting low stock levels and triggering alerts when a product’s quantity falls below five.


HOW TO RUN:
1.	Install Python (if not already installed), one must also have a basic knowledge of how to run a Python script.


STEPS TO RUN:
1.	Download the repository from [GitHub URL provided in this file at the top].
2.	Open a terminal or command prompt and navigate to the project directory.
3.	Run the program (python_pos_py)
4.	Follow Menu prompts to add items, remove items, view cart, checkout, view inventory and Exit.
5.	Login using the login feature to access the system 
6.	Navigate the menu options to launch the system 

REQUIRED MODIFICATIONS/FUTURE ENHANCEMENTS:
•	Customizable Options
1.	The system provides flexibility for inventory management by allowing users to update the product list, whether by adding new items or modifying existing ones. 
2.	Additionally, the discount threshold can be adjusted to align with business needs, ensuring that promotions and pricing strategies remain adaptable and effective.
3.	Implement a graphical user interface (GUI) for a more user-friendly experience.
4.	Sales Reports enhancements to facilitate the generation of daily, weekly and monthly sales summaries. 
5.	Membership loyalty programme, where members can benefit from personalized discounts.
6.	Implement barcode scanning
7.	Checkout and payment enhancement, this would facilitate the use of credit card and mobile payment such as Apple Pay etc. 
8.	Introducing a return policy feature on certain items over a specified period, this would also facilitate the implementation of a return handling mechanism that automatically updates stock upon return. 


ASSUMPTIONS and/or LIMIATION:
1.	The system is designed for cash transactions only, as it does not support card processing. 
2.	The system does not currently support refunds. Once a transaction is completed, items cannot be edited or reversed.
3.	Limited discounts as discounts are fixed at 5% for purchase of  $5000 or more.
4.	Currently, product selection is manual, the implementation of a barcode scanner would streamline check while reducing error
5.  No database management system to provide proper tracking of sales and/or inventory that can be tabled for reports
