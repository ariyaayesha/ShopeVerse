# 🛒 ShopVerse

ShopVerse is a simple yet functional supershop website that allows users to browse products, view deals, manage a shopping cart, and place orders. It includes features for checkout, order confirmation, and basic user authentication.

## 📂 Project Structure

```
.
├── index.html                # Homepage
├── best-sellers.html         # Best-selling products page
├── hot-deals.html            # Special offers page
├── products.html / .php      # Product listing
├── product-detail.html       # Product details view
├── checkout.html / .php      # Checkout process
├── order-confirmation.html   # Order confirmation page
├── invoice.php               # Invoice generation
├── simple-login.html         # Login form
├── simple-register.html      # Registration form
├── contact.html              # Contact page
├── css/style.css             # Main CSS styling
├── js/checkout.js            # Checkout functionality
├── js/order-confirmation.js  # Confirmation handling
├── script.js                 # Main JS logic
├── simple-auth.js            # Basic authentication logic
```

## ✨ Features

- **Product Browsing** – View product categories, details, and special deals.
- **Shopping Cart** – Add, update, and remove items before checkout.
- **Checkout System** – Collect customer details and process orders.
- **Order Confirmation & Invoice** – Show purchase details and generate invoices.
- **Basic Authentication** – Simple login and registration functionality.
- **Responsive Design** – Works on desktop and mobile devices.

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript
- **Backend**: PHP
- **Styling**: Custom CSS
- **Data Handling**: Basic PHP scripts
- **Database**: MySQL (for storing users, orders, and product data)

## 🚀 Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/your-username/supershop.git
cd supershop
```

### 2. Set up a local PHP server
If you have PHP installed:
```bash
php -S localhost:8000
```
Or use XAMPP/WAMP and place the project in the `htdocs` folder.

### 3. Database Setup
1. Create a MySQL database (e.g., `supershop_db`).
2. Import the provided SQL file into your database (if available, `database.sql`).
3. Update your PHP configuration files (e.g., `checkout.php`, `invoice.php`) with your database credentials:
```php
$servername = "localhost";
$username = "root";
$password = "";
$dbname = "supershop_db";
```
4. Ensure your MySQL server is running.

### 4. Open in browser
Visit:
```
http://localhost:8000
```
(or `http://localhost/supershop` if using XAMPP/WAMP).

## 📸 Screenshots
<img width="1917" height="943" alt="Screenshot 2025-08-13 111839" src="https://github.com/user-attachments/assets/c2b53bba-8008-4d8b-bde8-7de4a6b4cfba" />

<img width="1916" height="941" alt="Screenshot 2025-08-13 112127" src="https://github.com/user-attachments/assets/b3ff42fd-fc91-48bf-97ba-45aee4540307" />


