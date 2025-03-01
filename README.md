ShopForHome - Capstone Project 🏠🛍️
Welcome to ShopForHome, an e-commerce web application built as part of our capstone project. This project provides a seamless shopping experience for customers while offering admin functionalities for managing products, users, and discount coupons.

📌 Project Overview
ShopForHome is a full-stack application developed using:

Backend: ASP.NET 6.0 Web API
Frontend: Angular 19
Database: SQL Server
Authentication: JWT (JSON Web Token)
Styling: Bootstrap
This project supports role-based authentication, where:
✅ Customers can browse products, apply discount coupons, and purchase items.
✅ Admins can manage users, products, and coupons via a dedicated admin portal.

🎯 Features
🔹 User Features:
✅ User Registration & Login (JWT Authentication)
✅ View Products with Filtering & Sorting
✅ Search Products by Category & Price Range
✅ Apply Discount Coupons
✅ Add to Cart & Checkout

🔹 Admin Features:
✅ Manage Products (Add, Update, Delete)
✅ Manage Users (CRUD Operations)
✅ Create & Manage Discount Coupons
✅ View Sales Reports

![image](https://github.com/user-attachments/assets/50b50056-8cb9-470b-8afa-8e4d5920389a)

![image](https://github.com/user-attachments/assets/3ebbdf8f-41d7-48fa-9df4-b2bf8eee7576)


![image](https://github.com/user-attachments/assets/8a8e7c99-8aff-4e8f-b965-a32720f81eb4)


![image](https://github.com/user-attachments/assets/ebbc5d27-a3c1-4139-830d-21ca13ddd427)
![image](https://github.com/user-attachments/assets/f24767e8-dd2d-478a-9f5a-acc97978aca4)


📜 API Endpoints(important ones)
User Authentication
🔹 Register: POST /api/auth/register
🔹 Login: POST /api/auth/login

Products
🔹 Get All Products: GET /api/products
🔹 Get Product by ID: GET /api/products/{id}
🔹 Search Products: GET /api/search/filteredProducts

Admin Operations
🔹 Add Product: POST /api/products
🔹 Update Product: PUT /api/products/{id}
🔹 Delete Product: DELETE /api/products/{id}
🔹 Manage Users: GET/POST/PUT/DELETE /api/users

👥 Team Members
Abhishek Jaybhaye, Shreya Mehetre and Prateek Annand– Backend Development
Nikhil Parasuramputra and Somdev Chatterjee – Frontend Development
Abhishek Jaybhaye and Shreya Mehtre – Database & API Integration
Nabvitha S and Smdev Chatterjee– UI/UX Design

📌 Future Enhancements
🔹 Payment Gateway Integration
🔹 Order Tracking System


