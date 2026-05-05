# Book Management System

A lightweight, client-side web application for managing a digital library. This project allows users to browse a book catalog, manage a shopping cart, and provides an admin interface for library administration.

##  Features

* **Admin Panel**: Full CRUD (Create, Read, Update, Delete) functionality for the book database.
* **Storefront**: Interactive shop with real-time search filtering by title, author, or genre.
* **Wishlist & Cart**: Persistent storage of favorite books and shopping items using LocalStorage.
* **Responsive Design**: Clean UI built with modern CSS that works across different screen sizes.
* **Data Persistence**: All data is saved in the browser's `localStorage`, ensuring information remains after page refreshes.

## Technologies Used

* **HTML5 & CSS3**: Semantic structure and custom styling.
* **JavaScript (ES6+)**: Object-oriented approach using Classes (`BookManager`, `StorageManager`).
* **jQuery**: Used for DOM manipulation, event handling, and modal animations.
* **LocalStorage API**: For client-side data persistence.

## Project Structure

* `admin.html` - Interface for adding, editing, and deleting books.
* `shop.html` - The main customer interface for browsing and searching.
* `lists.html` - Overview of the user's Wishlist and Shopping Cart.

##  Getting Started

1.  Clone the repository or download the ZIP file.
2.  Open `shop.html` in any modern web browser.
3.  Navigate to the **Admin Panel** to add your own books or use the default pre-loaded catalog.

## 📝 License

This project is open-source and available under the [MIT License](LICENSE).
