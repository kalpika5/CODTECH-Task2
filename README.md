Name : MINNAMAREDDY KALPIKA
Company: CODETECH IT SOLUTIONS
ID:   CT4WD2607
DURATION: JUNE 20th, 2024 to JULY 20th, 2024
MENTOR:  Neela Santhosh Kumar

Project Overview:
Objective:
Build a simple e-commerce website where users can browse products, add them to a shopping cart, and proceed to checkout.

Key Features:
Product Listing: Display a list of products with their details.
Shopping Cart: Allow users to add and remove products from the cart.
Checkout: Provide a basic checkout form.
Components:
1. HTML (index.html):
The HTML file sets up the structure of the website, including the header, product listing, cart, and checkout form.

Header: Contains the website title and navigation links.
Main Content: Divided into three sections:
Products Section: Displays the list of products.
Cart Section: Displays the items added to the cart and the total price.
Checkout Section: Contains a form for users to enter their details and place an order.
2. CSS (style.css):
The CSS file styles the HTML elements to make the website visually appealing and responsive.

General Styles: Sets the font family, background color, and centers the main content.
Header: Styles the navigation links and header.
Product List and Cart Items: Styles the product and cart item containers, making them flexible and responsive.
Hidden Class: Used to hide the checkout section initially.
Form Styles: Styles the checkout form.
3. JavaScript (script.js):
The JavaScript file contains the logic for adding/removing products to/from the cart, displaying the cart, and handling the checkout process.

Products Array: An array of product objects with id, name, price, and image URL.
Cart Array: An array to store the items added to the cart.
Event Listeners:
DOMContentLoaded: Initializes the product display and sets up event listeners for the checkout button and form submission.
Functions:
displayProducts: Dynamically inserts product HTML into the product list section.
addToCart: Adds a selected product to the cart, or increments the quantity if it's already in the cart.
displayCart: Dynamically inserts cart item HTML into the cart section and updates the total price.
removeFromCart: Removes a product from the cart.
showCheckout: Displays the checkout form.
placeOrder: Handles the form submission, showing a success message, clearing the cart, and hiding the checkout form.
