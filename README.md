# Book Selling eCommerce Project : BookSmart

## About

This is a book-selling eCommerce project built using HTML, CSS, JavaScript, PHP, and MySQL. The project is designed to help understand the full-stack functionality of PHP while implementing essential eCommerce features. It includes all the necessary functionalities that a typical book-selling website should have.

## Features

- **User Authentication**: Users can register, log in, and manage their accounts.
- **Book Catalog**: Displays a list of available books with details such as title, author, price, and description.
- **Search & Filtering**: Users can search for books by title, author, or category.
- **Shopping Cart**: Add books to the cart and manage cart items before checkout.
- **Order Management**: Users can place orders, and admins can manage order statuses.
- **Admin Panel**: Admins can add, edit, and delete books, manage users, and track sales.
- **Payment Integration**: Supports checkout and payment processing (can be integrated with PayPal, Stripe, etc.).
- **Responsive Design**: Ensures a smooth user experience across different devices.

## Technologies Used

- **Frontend**: HTML, CSS, JavaScript
- **Backend**: PHP
- **Database**: MySQL

## Installation & Setup

### Prerequisites

- XAMPP/WAMP (for local development)
- PHP 7+
- MySQL Database

### Steps to Run the Project

1. Clone the repository:
   ```sh
   git clone https://github.com/JackSparrow1770/book_smart.git
   ```
2. Move the project folder to the XAMPP/WAMP `htdocs` directory.
3. Start Apache and MySQL from XAMPP/WAMP Control Panel.
4. Create a MySQL database, give it a name like 'bookstore\_db', and import the `book_shop_db.sql` file from the project.
5. Configure the database connection in `config.php`:
   ```php
   $conn = mysqli_connect("localhost", "root", "", "bookstore_db");
   ```
6. Open the browser and go to `http://localhost/booksmart`.

## Folder Structure

```
booksmart/
│-- index.php              # Home Page
│-- login.php              # User Login Page
│-- register.php           # User Registration Page
│-- cart.php               # Shopping Cart Page
│-- checkout.php           # Checkout Page
│-- admin/
│   │-- dashboard.php      # Admin Dashboard
│   │-- manage-books.php   # Add/Edit/Delete Books
│   │-- manage-orders.php  # Manage Orders
│-- assets/
│   │-- css/               # Stylesheets
│   │-- js/                # JavaScript Files
│-- config.php             # Database Connection
│-- database.sql           # Database Structure
```

## Future Enhancements

- Implement user reviews and ratings.
- Add email notifications for order confirmations.
- Integrate additional payment gateways.
- Enhance UI/UX with modern frontend frameworks.

## Contributing

Feel free to fork the repository, create feature branches, and submit pull requests.

## License

This project is open-source and available under the [MIT License](LICENSE).

