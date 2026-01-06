# E_Commars_Full

E-commerce Website: SetUpSprint
This project is an e-commerce website developed using HTML, CSS, JavaScript, PHP, and MySQL. It serves as a platform for users who are interested in building their own PC setups by providing them with a variety of PC components for sale. The website offers a range of PC components such as processors, graphics cards, motherboards, RAM, storage devices, power supplies, and peripherals.

Features :
User Authentication: Users can sign up, log in, and log out securely to access the website's features and make purchases.
Product Listings: The website displays a wide range of PC components categorized by type, and brand, allowing users to browse and search for specific items easily.
Shopping Cart: Users can add products to their shopping cart, review the items in their cart, and proceed to checkout to complete their purchases.
Checkout Process: The website facilitates a secure checkout process where users can review their order details, enter shipping and payment information, and place their orders.
User Profile: Registered users have access to a profile page where they can view their order history, update their account information, and manage their preferences.
Overall, this e-commerce website provides a convenient and user-friendly platform for individuals who are building their PC setups to browse, select, and purchase PC components efficiently.

Project Setup :
if XAMPP is installed on your Computer Clone this repository in “htdocs” folder in your XAMPP installation directory (e.g., C:\xampp\htdocs for Windows) if not download it in Here
git clone https://github.com/Harsh166550/E_Commars_Full
start Apache and Mysql :

if mysql is running on a different port change the port number in includes/database.php and DB-setup/scraping_products_data
Setup the database :

open "http://localhost/phpmyadmin" in your browser and create a database named "setupsprint_ecommerce_website";
execute the SQL queries inside the DB-setup folder
execute the Python code to load data into the DB (all data was scraped from another website)
Open the project : "http://localhost/homePage.php"



