# OOAD_Project

Banking Management System - Functionalities Overview
File Functionalities:
1. AccountConfiguration.java
Functionality: Manages the creation of accounts and customers.

Features:
Allows users to create different types of accounts like Savings Max Account, Current Account, and Loan Account.
Validates the opening balance for accounts, ensuring it meets minimum balance requirements.
Provides options to add multiple accounts for a customer.
Displays customer-account details including customer ID, name, account type, and balance.

2. ManageAccountConfiguration.java
Functionality:
Handles account management operations.

Features:
Provides a user interface to select a customer and manage their accounts.
Allows deposit and withdrawal operations, considering specific conditions like minimum balance requirements for Savings Max Accounts.
Displays a user-friendly menu for deposit, withdrawal, and account details.
Supports multiple actions in account management and prompts for continuation.

4. ProductConfiguration.java
Functionality:
Manages the creation and display of banking products and services.


5. AccountUtility.java

Features:
Enables the creation of various types of banking products like Savings Max Account, Current Account, and Loan Account.
Supports the addition of multiple services to each type of product.
Provides a user interface to create and display products along with their associated services.
Helps visualize available products and services in an organized manner

1. Menu Creation:
Provides options to create services, display services, create products, and display products.

createService():
Enables the creation of various banking services, allowing users to input service details like code, name, and rate.
displayService(ArrayList<Service> serviceList):
Displays the available services along with their details.

2. Banking Operations:
Allows users to perform various banking operations:

Create Customer:
Invokes the creation of a new customer, enabling the addition of multiple accounts with associated services.

Manage Account:
Handles account management operations, including deposit, withdrawal, and account display.

Display Customer:
Displays customer details along with their associated accounts and balances.

TransactionBill:
Calculates transaction costs for selected accounts based on the number of transactions and service rates.
