# Zaiko
An Inventory and Billing Management (Netbeans Application)

## Functionalities
### Home Page
You can choose to:
1. Update Available Stock's Details
2. Create a New Bill
3. Get Report

### Updating Stock
Under the Update Stock function, you are asked to enter a valid product ID and the details of the Product pertaining to that ID is displayed to the shopkeeper.The shopkeeper can update the available quantity or the price of the product and appropriate messages are displayed to notify in the case of Incorrect IDs or if all necessary fields aren't filled.
To denote successful updates, the system displays the updated details of that product. Furthermore, if the user wants to add a new product in the database, an Add Stock option is available and they are also enabled to View Stock.

#### Add Stock
In the Add Stock function, the user is requested to enter all the details of the new product and the system check if the Product already exists, if all the data types are appropriate and the relevant notifications are sent to the shopkeeper.

#### View Stock
This function shows the contents of the Stock Database.

### Bill Creation
In the Create Bill function, the product(s) are chosen according to Product ID. If there are any issues during data entry, like, Invalid Product ID or Limited Quantity an immediate message is sent. The price is calculated according to the quantity and after all products are entered, the user can choose to Complete Bill and get the total or Update the bill by either removing a product or changing the quantity. The final bill and amount is displayed.

#### Updating Bill
The bill can be updated by the user who is enabled to remove a valid product from the purchase or update the quantity into an allowed amount.

### Report
It shows the bills generated between the specified dates and the total amount of sales during that period.

## Functional Decomposition Diagram
![image](https://user-images.githubusercontent.com/67183417/211072712-b09c632d-8fb1-4d34-88e8-805b0cb8f3a8.png)

## Architecture Diagram
![image](https://user-images.githubusercontent.com/67183417/211073373-f6fd5951-e753-4478-8928-a18ade4300c8.png)

## Detailed System Design
![image](https://user-images.githubusercontent.com/67183417/211073089-c00a0655-9783-4c98-9410-5c79a3d52974.png)

## Entity Relationship Diagram
![image](https://user-images.githubusercontent.com/67183417/211073604-dfce3425-c631-497e-96c0-f84651cbc90d.png)
