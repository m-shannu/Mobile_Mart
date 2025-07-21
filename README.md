📱 Mobile Mart – Admin-Controlled Inventory & Customer Availability Web App
A full-stack web application to digitize and streamline mobile store and repair management.
Built with Spring Boot and React.js, Mobile Mart provides secure, role-based access for admins and customers.

🚀 Features
👤 User Features
Browse products by category and brand

View product details with images and pricing

Search and filter products

Book repair service slots

Manage personal profile

🛠️ Admin Features
Add, update, delete products

Manage product categories

Add and manage available repair slots

View and manage user bookings

📝 Problem Statement
Many mobile service centers still manage repair bookings and inventory manually, leading to:

Long wait times

Miscommunication and errors

Lack of proper tracking

Poor customer experience

💡 Proposed Solution
Mobile Mart offers a centralized digital platform to:

Allow customers to view real-time inventory and book repairs online

Empower admins to efficiently manage inventory, categories, and appointments

Provide a secure, fast, and user-friendly system with proper data storage

🎯 Objectives
✅ Develop a user-friendly online store interface
✅ Allow admins to manage inventory and bookings
✅ Provide secure authentication and REST APIs
✅ Store and manage data in a robust database

🖥️ Tech Stack
Layer	Technology
Frontend	React.js, Axios, React Router, HTML, CSS, Bootstrap
Backend	Spring Boot, Spring Data JPA
Database	MySQL
Tools	Spring Tool Suite, VS Code, Postman, MySQL Workbench

🧰 System Architecture
css
Copy
Edit
[React Frontend] → REST API → [Spring Boot Backend] → [MySQL Database]
Follows the MVC architecture:

Model: JPA Entities & Database

View: React Components

Controller: REST API Endpoints

📑 API Highlights
GET /api/items — Get all items

POST /api/items — Add new item

DELETE /api/items/{id} — Delete an item

POST /api/bookings — Book repair slot

🖼️ Frontend Highlights
User dashboard with available products and repair slots

Admin panel for managing products, categories, and slots

Axios for API calls

React Router for navigation

⚙️ Challenges Faced
Integrating React with Spring Boot backend

Handling CORS policy errors

Designing responsive layouts

Ensuring smooth CRUD operations

🎓 Learning Outcomes
Building full-stack web applications

Integrating Spring Boot REST APIs with React frontend

Testing APIs using Postman

Performing CRUD operations on MySQL

🔮 Future Enhancements
Integrate online payment gateway

Add real-time order tracking

Advanced search and filtering
