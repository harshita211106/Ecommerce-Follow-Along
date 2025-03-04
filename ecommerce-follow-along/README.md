# Ecommerce-Follow-Along
Milestone 1: Project Overview to summarize what was covered in the session
Summary:
     This repository contains the follow-along project for building a full-fledged E-Commerce Application using the MERN stack (MongoDB, Express.js, React.js, and Node.js)
     
Objectives:
      Understand the structure of a MERN stack project.
      Learn how to set up a project repository and organize it.
      Grasp the core features and functionalities of an e-commerce application, such as user authentication, product management, and order handling.

Key features:
    1. User Authentication: Make sure users can securely log in and register with ease. Passwords will be safely hashed, and users will get tokens to stay logged in without needing to enter their credentials every time.
    2. Product Management: Admins will have the power to add, edit, or delete products with all the details like name, price, and description. Shoppers can browse, search, and filter products easily, and every product entry will be double-checked to ensure no mistakes slip through.
    3. Order Handling: Customers can place orders, track their progress (like "Shipped" or "Delivered"), and view their purchase history. Admins will have tools to manage all orders, update their status, and handle requests like cancellations.
    4. Database Schema Design: MongoDB will store all the app's data, from users and products to orders. The database will be thoughtfully structured to link related data 
    5. Frontend Development: The user interface will be built with React.js, ensuring it’s both beautiful and easy to use. From a smooth shopping experience to a dashboard for admins to manage everything, the app will work seamlessly on all devices, big or small.
    6. Backend Development: The backend will handle all the heavy lifting, like processing data, handling business logic, and making sure everything runs smoothly. Node.js and Express.js will keep things robust and scalable, with extra layers of security to protect sensitive data.


Milestone 2: Project Setup and Login Page

In this milestone, we focused on setting up the initial front-end structure and implementing the login page for the application. Key achievements include:

Front-End Framework: Set up the React framework with Vite for a fast and modern development experience. Folder Structure: Organized the src folder to include separate directories for components, pages, and assets to improve scalability and maintainability. Login Page Implementation: Developed a basic login page (Login.jsx) that includes a user interface for email and password input. Incorporated validation logic to ensure proper user input. Routing: Implemented React Router for navigation and created routes for the login and signup pages. Styling: Added basic styling using CSS (App.css) to ensure a clean and user-friendly design. Git Integration: Added the new files to version control and committed progress to the GitHub repository. This milestone lays the groundwork for creating the front-end interface and interaction logic for the application.





Milestone 3: Project Setup for Backend  
In this milestone, the foundational backend structure was successfully established.


- Backend Folder Structure: The project is organized into various folders such as `config/`, `controller/`, `db/`, `middleware/`, `model/`, `utils/`, `products/`, and `uploads/`. This structure ensures modularity and scalability.
- **Database Integration:** A MongoDB connection has been established using Mongoose, allowing efficient interaction with the database.
- **Environment Configuration:** An `.env` file is implemented to securely store sensitive information like database credentials.
- **Middleware Implementation:** Middleware for authentication, error handling, and request processing has been added.
- **Utility Functions:** Custom utility functions, including a reusable error handler, have been introduced to enhance code maintainability.
- **Git Integration:** A `.gitignore` file has been included to exclude unnecessary files, and all changes have been committed to GitHub.
