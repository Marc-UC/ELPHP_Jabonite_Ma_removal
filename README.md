# Book Management API
 "Book Management API" allows users to register, log in, and manage a collection of books through authenticated API requests. This project demonstrates full CRUD functionality, authentication using Laravel Sanctum, and proper API route structuring.

# Features:
User Authentication

Register new users with validation

Secure login using hashed passwords

Token-based authentication with Laravel Sanctum

Logout functionality with token revocation

# Book Management (CRUD)

Create, Read, Update, Delete operations for books

Books have title, author, and description fields

Public routes for viewing books

Protected routes (auth required) for creating, editing, and deleting books

# API Routes

/api/register - User registration

/api/login - User login (returns API token)

/api/logout - Logs out the authenticated user

/api/books - List all books or create a new book

/api/books/{id} - View, update, or delete a specific book
