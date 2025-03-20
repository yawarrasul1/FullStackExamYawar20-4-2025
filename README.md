# FullStackExamYawar20-03-2025
 # E-Commerce Full Stack Application
 
 Project Description
 
 This is a full-stack e-commerce web application built using Angular, Node.js, Express, MongoDB.  
 It supports product listings, cart management, orders, and detailed reports like sales, top products, user summaries, and inventory tracking.
 
 ---
 
 Features
 
 - Frontend: Angular LazyLoading.
 - Backend: Node.js with Express and MongoDB.
 - Product Listing with search, filter, and pagination.
 - Cart Functionality.
 - Order Management.
 - Reports: Sales, top-selling products, user orders summary, and low-stock inventory.
 - Error Handling for API responses (including 403 errors).
 - Authentication with JWT (optional).
 
 
 Setup and Installation
 
 1️ Clone the Repository  
 
 git clone https://github.com/your-repo-link.git
 
 
 2️ Backend Setup
 UNZIP both the folders
 Go to the backend folder
   npm install  
   Create a .env file in the backend folder
   Add environment variables to .env
       
       PORT=5000
       MONGO_URI=mongodb+srv://<username>:<password>@cluster0.mongodb.net/ecommerce  
       JWT_SECRET=your-secret-key
 
 Note:
 Replace <username> and <password> with your MongoDB credentials. (You can use any URI from MongoDB Atlas)
 Set a strong JWT_SECRET for authentication.
 
 3️ Frontend Setup
      Go to the frontend folder
      Install frontend dependencies
       npm install  
      Run the Development Servers
 
   Start the backend server
       npm install
       npm start
   Backend runs at: http://localhost:5000
 
   Start the frontend server
       ng serve --open
   Frontend runs at: http://localhost:4200
 
 * API Endpoints
 **Products**
 GET /api/products → Fetch products with search, filter, pagination
 GET /api/products/:id → Get product details
 POST /api/products → Add a product
 **Orders**
 POST /api/orders → Create an order
 GET /api/orders/user/:id → Get user orders
 **Reports**
 GET /api/reports/sales → Get sales report
 GET /api/reports/top-products → Get top-selling products
 GET /api/reports/user-summary → Get user orders summary
 GET /api/reports/inventory → Get low-stock products
 **Error Handling**
 403 Forbidden → For unauthorized requests (e.g., missing or invalid tokens).
 500 Server Error → For any other backend issues.
   
 **Improvements To Add** (Future Features)
 Wishlist feature
 Product reviews & ratings
 Admin panel for inventory control
 Payment gateway integration
 Centralized Api Management
 
 
 ✨ Author
 👨‍💻 Yawar Rasul
 📧 Email: yawar7867@gmail.com
