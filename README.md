🚀 Overview
This project is an e-commerce website developed through a series of milestones, progressively adding features to build a complete and functional application.

📚 Table of Contents
Overview
Tech Stack
Milestones
Milestone 1: Project Setup
Milestone 2: Frontend & Backend Initialization
Milestone 3: Backend Structure & Server Setup
Milestone 4: Creating User Model and Controller
Milestone 5: Sign-Up Page & Form Validation
Milestone 6: Secure User Registration
Milestone 7: User Login & Authentication
Milestone 8: Product Card Component & Homepage Layout
Milestone 9: Product Input Form
Milestone 10: Product Schema & Endpoint Creation
How to Run the Project
Next Steps
Contributing
License
🛠 Tech Stack
Frontend: React.js, Tailwind CSS
Backend: Node.js, Express.js
Database: MongoDB
File Uploads: Multer
Password Encryption: bcrypt
Version Control: Git, GitHub
📌 Milestones
Milestone 1: Project Setup
✅ Goals:

Created and updated README.md file.
Initialized GitHub repository for version control.
Milestone 2: Frontend & Backend Initialization
✅ Goals:

Project Folder Structure: Organized files into separate frontend and backend directories.
React Frontend Setup: Initialized a React application for building the user interface.
Node.js Backend Setup: Set up a simple Node.js server for API integration in future milestones.
Tailwind CSS Configuration: Integrated and configured Tailwind CSS for modern, responsive styling.
Login Page Development: Created a login page with functionality and styling.
Milestone 3: Backend Structure & Server Setup
✅ Goals:

Backend Folder Structure: Created a structured hierarchy for organizing routes, controllers, models, and middleware.
Server Setup:
Used Node.js and Express.js to create a backend server.
Configured the server to listen on a designated port.
Database Connection:
Integrated MongoDB for efficient data storage.
Confirmed the connection between the server and MongoDB.
Error Handling:
Provided clear error messages for better debugging and user feedback.
Milestone 4: Creating User Model and Controller
✅ Goals:

User Model: Defined the structure of user data with attributes like name, email, password, and profile picture.
User Controller: Handled user-related actions such as registration and data retrieval.
Multer Integration: Enabled file uploads for storing user profile pictures.
API Routes: Created endpoints for user creation and fetching user details.
README Update: Documented progress and updated repository.
Milestone 5: Sign-Up Page & Form Validation
✅ Goals:

Sign-Up Page UI: Designed a clean and user-friendly sign-up form with fields for name, email, and password.
Form Validation:
Ensured the email follows the correct format.
Implemented password security criteria (minimum length, special characters, etc.).
User Registration Flow: Integrated frontend form submission with the backend API.
Error Handling: Displayed validation errors to users in real-time.
README Update: Documented progress and updated repository.
Milestone 6: Secure User Registration
✅ Goals:

Password Encryption:
Used bcrypt to hash passwords before storing them in the database.
Ensured no plaintext passwords are stored.
Secure Data Storage:
Stored the user's encrypted password along with other necessary details in MongoDB.
Updated API Endpoints:
Modified the user registration endpoint to handle password hashing securely.
Security Compliance:
Followed best practices for protecting user credentials.
README Update:
Documented progress for Milestone 6 and updated the repository.
Milestone 7: User Login & Authentication
✅ Goals:

Login Endpoint: Created a backend endpoint for user login and verified user credentials.
Password Validation: Utilized bcrypt for secure password comparison.
Authentication Flow: Authenticated users based on matching hashed passwords.
Security Considerations: Ensured secure handling of user credentials.
README Update: Updated with details about the user login functionality.
Milestone 8: Product Card Component & Homepage Layout
✅ Goals:

Card Component Creation: Designed a reusable card component for displaying product details.
Homepage Layout Design: Created a responsive grid layout for displaying multiple product cards.
Dynamic Data Display: Implemented dynamic rendering of product cards using mapping.
Consistency & Responsiveness: Ensured consistent styling and responsive design.
README Update: Documented progress and learning outcomes for Milestone 8.
Milestone 9: Product Input Form
✅ Goals:

Product Form Creation:
Designed a form for inputting product details such as name, description, price, and category.
Included fields for uploading multiple product images.
Image Upload Functionality:
Implemented file input to accept multiple images.
Configured frontend to preview selected images before submission.
Form Validation & Error Handling:
Ensured all required fields are filled out.
Displayed validation errors for incomplete or incorrect inputs.
Integration with Backend:
Connected the form to the backend API for product creation.
Stored product details and images in MongoDB.
User Experience Enhancements:
Provided a clean and user-friendly UI for the product input form.
Added real-time feedback for image uploads and form validation.
README Update:
Documented the progress and learning outcomes for Milestone 9.
Updated the repository with details about the product input form.
Milestone 10: Product Schema & Endpoint Creation
✅ Goals:

Product Schema Creation:
Designed a Mongoose schema for product details including name, description, price, and image URL.
Ensured each field has proper validation (e.g., required fields, correct data types).
Endpoint Creation:
Built a POST endpoint to receive product data.
Validated and saved the product details to MongoDB.
Why Validation?
Ensures that only valid data is saved in the database, maintaining data integrity and preventing errors.
Security Enhancements:
Implemented additional validation and data integrity measures to ensure accurate and secure data storage.
Next Steps (Optional):
Experiment with adding features such as admin access control to allow only admins to upload products or creating user profiles with roles for managing the shop.
Milestone 11: Dynamic Homepage with Product Data
✅ Goals:

1️⃣ Backend - Fetch All Products
Created an API endpoint to retrieve all product data stored in MongoDB.
Used Express.js and Mongoose to fetch and send product details as JSON.
2️⃣ Frontend - Fetch & Display Data Dynamically
Created a function to fetch product data from the backend.
Passed the received data to the existing Product Card Component.
Used .map() to dynamically render each product on the homepage.
3️⃣ Why This Matters?
Enables dynamic content loading from the database instead of hardcoded values.
Improves scalability and flexibility as new products are added.
4️⃣ Submission Steps
✅ Pushed the updated code to the GitHub repository.
✅ Updated the README.md file with Milestone 11 details.
✅ Shared the repository link for submission.
Milestone 12: My Products Page - Filtering by User Email
✅ Goals:

1️⃣ Backend - Fetch Products by User Email
Created an API endpoint to retrieve only the products added by the logged-in user.
Used Express.js and Mongoose to filter products based on the user's email stored in MongoDB.
Ensured secure and efficient querying to fetch only relevant data.
2️⃣ Frontend - Fetch & Display User-Specific Products
Created a function to fetch products linked to the logged-in user's email.
Passed the received data to the existing Product Card Component.
Used .map() to dynamically render only the user's products on the "My Products" page.
3️⃣ Why This Matters?
Enables personalized product listings based on the logged-in user's email.

Improves data filtering skills, ensuring only relevant data is sent to the client.

Enhances user experience by displaying only their added products instead of all products.

Milestone 13: Complete Project Documentation & Code Refactoring
✅ Goals:

Code Refactoring:
Improved code structure, ensuring modular and maintainable components.
Removed unnecessary files and optimized logic.
Comprehensive README Update:
Documented all features and milestones clearly.
Added setup instructions and usage details for new contributors.
Bug Fixes:
Fixed known issues related to authentication and data fetching.
Enhanced error handling for better debugging.
Deployment Preparation (Optional):
Structured code for potential deployment on platforms like Vercel or Heroku.
Final Submission:
Pushed the updated code to GitHub.
Ensured project documentation is complete and easy to understand.
Milestone 14: Product Deletion Feature
✅ Goals:

1️⃣ Backend - Delete Product by ID
Created a DELETE API endpoint in Express.js to delete a product using its unique ID.
Used Mongoose to find and remove the product from MongoDB.
Ensured proper error handling if the product does not exist.
✅ Code Snippet:

app.delete("/api/products/:id", async (req, res) => {
    try {
        const { id } = req.params;
        const deletedProduct = await Product.findByIdAndDelete(id);

        if (!deletedProduct) {
            return res.status(404).json({ message: "Product not found" });
        }

        res.json({ message: "Product deleted successfully" });
    } catch (error) {
        res.status(500).json({ message: "Error deleting product" });
    }
});



## ▶ How to Run the Project  
1. Clone the repository:  
   ```bash  
   git clone https://github.com/your-username/E_Commerce_Follow_Along.git  
   cd E_Commerce_Follow_Along  
Install dependencies for both frontend and backend:

cd frontend && npm install  
cd ../backend && npm install  
Run the backend server:

npm start  
Run the frontend application:

cd frontend  
npm start  
Open http://localhost:3000/ in your browser.