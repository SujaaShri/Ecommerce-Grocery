QuickMart: FULL-STACK eCommerce web application for seamless Grocery shopping

QuickMart is a dynamic and user-friendly online grocery shopping platform. It allows customers to explore products by category, manage their cart, proceed through a secure checkout and multi-mode payment process, and track their order history, all through a responsive and intuitive interface. An integrated admin portal empowers backend management of inventory and order delivery.

Project Description
QuickMart is a full-fledged eCommerce web application developed as part of a web programming project, aimed at replicating the core functions of an online supermarket. Designed to replicate a real-world grocery shopping experience, the platform streamlines the entire process, from product browsing to order placement and management. It offers a secure, interactive, and responsive interface for both users and administrators, emphasizing usability, data validation, and modular backend control. This project demonstrates the practical application of web development skills in creating maintainable and end-to-end operable online retail system

Technologies Utilized
The following technologies were employed in the development of this project:
Frontend: HTML, CSS, JavaScript
JavaScript Library: jQuery
Backend: Node.js with Express.js
Database: MongoDB
Development Tools: Visual Studio Code,chrome

System Configuration
To set up and run the system locally, please follow these steps:
Install Node.js on your machine.
Install MongoDB version 3.4 or above.
Utilize Visual Studio Code as your code editor (recommended for optimal development experience).
Install the necessary Node Package Manager (NPM) packages.

NPM Dependencies
The following essential NPM package are required
express
mongoose
body-parser
cookie-parser
express-session
path

Project Initialization
To initialize and run the project, execute the following commands:
1. Clone the repository: 
git clone https://github.com/SujaaShri/Ecommerce-Grocery_QuickMart

2. Install dependencies:
npm install

3. Start the server:
node adminserver.js - to start the admin portal
node server1.js - to start the user pages

4. Run the server:
User side: localhost:5000/homepg.html
Admin side: localhost:7000/login
User name: Admin#0x
Password: Admin@0x
, where x is 1-9

Core Features
The application incorporates the following core functionalities:
1. User Signup and Login
•	Users can create a new account or log in with existing credentials.
•	Validation is handled to ensure secure authentication.
•	To set up a new password OTP is any 4-digit number (mock)

2. Home Page
•	Displays multiple categories of grocery products.
•	Users can filter products by category and sort by price.
•	Users can search for a product in the search bar.

3. Cart Page
    Users can:
•	Add items to the cart.
•	Increase or decrease item quantities.
•	Remove entire products from the cart.
•	Displays dynamic pricing based on quantity changes.

4. Checkout Page
•	Collects essential delivery information like pincode and mobile number.
•	Built-in validation for:
•	Valid chennai city pincode.
•	10-digit mobile numbers.
•	Proceeds to the payment page upon successful validation.

5. Payment Page
    Offers 4 payment modes:
•	Card
•	UPI
•	Net Banking
•	Cash on Delivery (COD)
   
Input fields have proper validation:
•	Card number format
•	CVV
•	UPI ID format
•	Mobile number validation

6. My Orders Page
•	Displays all past and current orders.

Each order includes:
•	Product details
•	Delivery status
•	Date/time
•	Includes "Cancel Order" button for the orders with delivery status placed or processing.

7. Admin Page
   Admins can log in using a verified admin name and ID.
   
 Functionalities include:
•	Add new products
•	Update product stock, price, description, and current price
•	Update the delivery status of placed orders

GitHub Repository
The source code for this project is hosted on GitHub:
https://github.com/SujaaShri/Ecommerce-Grocery_QuickMart
Credits
This project is a collaborative effort developed by a team of five members:
Team Members:
Sujaa Shri S  
Ramya M
Elakiya R 
Thanusha E
Mugeshwaran E

Conclusion
This project serves as a robust foundation for developing real-world web applications, emphasizing user experience and fundamental backend integration. Future enhancements are planned, including the replacement of static HTML components with dynamic React components and the integration of secure payment gateways.
We welcome constructive feedback and contributions to further improve and expand this project.
