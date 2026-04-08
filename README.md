## MERN Full Stack Ecommerce Web Application

A full-stack eCommerce web application built using the MERN stack (MongoDB, Express.js, React.js, Node.js).
This project provides a complete online shopping experience including product browsing, cart management, and user authentication.

## 🚀 Features

- 👤 User Features
  - Registration & Login (Authentication)
  - Browse Products
  - Search & Filter Products
  - Add to Cart / Remove from Cart
  - Checkout System
  - Order Management
- 🛠️ Admin Features
  - Add / Edit / Delete Products
  - Manage Users
  - Manage Orders
- ⚙️ General Features
  - Responsive UI
  - REST API integration
  - Secure backend with JWT authentication
  - Database integration using MongoDB
- 🧑‍💻 Tech Stack
  - Frontend
    - React.js
    - CSS / Bootstrap / Tailwind (if used)
    - Axios
  - Backend
    - Node.js
    - Express.js
  - Database
    - MongoDB (Mongoose)


```
Mern-Full-stack-Ecommerce-Web-application/
│
├── frontend/        # React frontend
├── backend/        # Node + Express backend
├── models/         # Database models
├── routes/         # API routes
├── controllers/    # Business logic
├── config/         # Database config
└── package.json
```

## Installation & Setup
 - 1️⃣ Clone the repository
   - Backend
     ```
     git clone https://github.com/Oudarja/Mern-Full-stack-Ecommerce-Web-application.git
     cd Mern-Full-stack-Ecommerce-Web-application
     ```
 - 2️⃣ Install dependencies
   - Frontend
      ```
        cd backend
        npm install
      ```
 - 3️⃣ Environment Variables
   - Create a .env file in the backend folder and add:
     ```
     PORT=5000
     MONGO_URI=your_mongodb_connection_string
     JWT_SECRET=your_secret_key
     ```
 - 4️⃣ Run the application
   - Run backend
     ```
     npm run server
     ```
   - Run frontend
     ```
     npm start
     ```
## API Endpoints (Example)
### Method	Endpoint	Description
  - GET	/api/products	Get all products
  - GET	/api/products/:id	Get single product
  - POST	/api/users/login	User login
  - POST	/api/users/register	User register
  - POST	/api/orders	Create order
