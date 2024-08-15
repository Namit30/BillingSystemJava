# Hotel Billing System

This Java program is a hotel billing system that allows users to register, log in, view a menu, place an order, and generate a bill. 

## **Features**

- **Menu Management**: The program initializes a menu with various food items and their prices.
- **User Authentication**: Users can register or log in. Registered users' data is saved to a file (`users.txt`), and the program checks this file to validate users.
- **Order Placement**: Once logged in, users can select items from the menu to create an order.
- **Bill Generation**: After placing an order, the program generates a detailed bill, showing the order summary, total price, and other details. The bill is displayed on the console and saved to a text file.

## **Key Components**

### User Management
- Users can register by creating a username and password.
- The program validates users against stored credentials in `users.txt`.

### Menu Display
- The menu is displayed with item numbers, names, and prices.

### Order Processing
- Users can add items to their order by selecting item numbers.
- The order is saved to a list associated with the current user.

### Bill Generation
- The bill includes the hotel name, date, served by, and a detailed list of items ordered with their prices.
- The total cost is calculated and displayed.
- The bill is saved as a text file with a unique filename.

## **Example Usage**

1. **Login/Registration**: The user selects between logging in or registering.
2. **Order Placement**: The user views the menu and adds items to their order.
3. **Bill Generation**: The program generates a formatted bill, displays it, and saves it as a file.

## **Conclusion**

This program is a basic implementation of a hotel billing system, demonstrating user authentication, menu management, order processing, and bill generation. It's an excellent starting point for learning about file handling, user management, and basic billing operations in Java.

## **Getting Started**

To run this project:

1. Clone the repository.
2. Open the project in your favorite Java IDE.
3. Run the `Main.java` file to start the application.

## **Contributing**

Feel free to fork this repository, submit issues, and send pull requests. Contributions are always welcome!
