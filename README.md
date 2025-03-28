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


Milestone 15: Navbar Component & Navigation

✅ Goals:

Created a new Nav component with links to all pages:

Home

My Products

Add Product

Cart

Made the Navbar responsive for all screen sizes.

Ensured smooth navigation across all pages.

Improved user experience by providing consistent and intuitive navigation.

✅ Implementation Steps:

Created a Navbar component:

Developed a reusable Navbar component with navigation links.

Styled the Navbar using Tailwind CSS to ensure responsiveness.

Added Navbar to all pages:

Imported and placed the Navbar in every relevant page.

Ensured proper routing and navigation using React Router.

Made the Navbar responsive:

Used flexbox and media queries to adjust the Navbar layout.

Implemented a mobile-friendly dropdown menu.

✅ Why This Matters?

Provides a seamless navigation experience for users.

Improves usability and accessibility across different devices.

Enhances code reusability by using a single component across multiple pages.

✅ Submission Steps:

Pushed the updated code to the GitHub repository.

Updated the README.md file with Milestone 15 details.

Shared the repository link for submission.

▶ How to Run the Project

Clone the repository:

git clone https://github.com/your-username/E_Commerce_Follow_Along.git  
cd E_Commerce_Follow_Along  

Install dependencies for both frontend and backend:

cd frontend && npm install  
cd ../backend && npm install  

Run the backend server:

cd backend
npm start  

Run the frontend application:

cd frontend  
npm start  

Open http://localhost:3000/ in your browser.


Milestone 16: Product Info Page
✅ Goals:

1️⃣ Creating the Product Info Page
Designed a dedicated page to display detailed product information, including:
Product Name
Description
Price
Image(s)
2️⃣ Adding Quantity Selection & "Add to Cart" Button
Implemented a quantity selector to allow users to choose the desired quantity.
Added an "Add to Cart" button to store selected items in the cart.
3️⃣ Dynamic Routing for Product Details
Utilized React Router to create dynamic routes for each product.
Fetched product details based on the product ID from the URL.
4️⃣ Enhancing User Experience
Ensured mobile responsiveness for smooth browsing on all devices.
Implemented loading indicators for better user experience.
5️⃣ Submission Steps
✅ Pushed the updated code to the GitHub repository.
✅ Updated the README.md file with Milestone 16 details.
✅ Shared the repository link for submission.


Milestone 17: Add to Cart Functionality
✅ Goals:

1️⃣ Update User Schema for Cart Functionality
Modified the user schema to include a cart field.
Structured the cart field to store an array of product objects containing:
Product ID
Name
Price
Quantity
2️⃣ Backend - Add to Cart Endpoint
Created an endpoint to receive product details and store them in the user's cart.
Ensured secure handling of requests and efficient database updates using MongoDB & Mongoose.
3️⃣ Frontend - Add to Cart Integration
Connected the "Add to Cart" button from the Product Info Page to the backend API.
Stored cart data in the database and updated the UI dynamically.
4️⃣ User Experience Enhancements
Implemented a notification system to confirm when a product is added to the cart.
Ensured real-time cart updates without needing to refresh the page.
5️⃣ Submission Steps
✅ Pushed the updated code to the GitHub repository.
✅ Updated the README.md file with Milestone 17 details.
✅ Shared the repository link for submission.



Milestone 18: Cart Page and Checkout Functionality
✅ Goals:

1️⃣ Creating the Cart Page
Designed a Cart Page to display:
List of added products
Product images, names, prices, and quantities
Total cart value
Implemented a Remove from Cart button for each item.
2️⃣ Backend - Fetch & Update Cart
Created an endpoint to retrieve cart items from the database.
Implemented an API to update product quantities in the cart.
Ensured secure cart data management for logged-in users.
3️⃣ Checkout Functionality
Added a Checkout button that:
Confirms the order
Clears the cart after a successful purchase
Redirects users to an order confirmation page
Integrated a payment gateway placeholder for future improvements.
4️⃣ User Experience Enhancements
Provided real-time cart updates when quantities change.
Displayed subtotal and total price dynamically.
Ensured a mobile-friendly UI for a seamless experience.
5️⃣ Submission Steps
✅ Pushed the updated code to the GitHub repository.
✅ Updated the README.md file with Milestone 18 details.
✅ Shared the repository link for submission.



Milestone 19: Cart Quantity Management
✅ Goals:

1️⃣ Frontend - Cart Page UI Enhancements
Added + and - buttons next to each product to modify its quantity.

Ensured real-time updates for accurate pricing adjustments.

2️⃣ Backend - Quantity Management Endpoint
Created two API endpoints to increase and decrease product quantity in the cart.

Integrated logic to prevent negative quantities and handle item removal automatically when reduced to zero.

3️⃣ Enhancing User Experience
Ensured instant feedback when quantity adjustments are made.

Maintained a clean UI design with clear quantity controls.

4️⃣ Submission Steps
✅ Pushed the updated code to the GitHub repository.

✅ Updated the README.md file with Milestone 19 details.

✅ Shared the repository link for submission.

Milestone 20: Profile Page
✅ Goals:

1️⃣ Backend - User Data Endpoint
Created an API endpoint to send all user data including profile details and addresses.

Ensured the endpoint is secure and accessible only to authenticated users.

2️⃣ Frontend - Profile Page UI
Designed a Profile Page that displays:

Profile Photo

Name

Email

List of Addresses

Added a clear "Add Address" button for adding new addresses.

Displayed "No address found" when no addresses are available.

3️⃣ Enhancing User Experience
Ensured the profile page design is clean and easy to navigate.
4️⃣ Submission Steps

✅ Pushed the updated code to the GitHub repository.

✅ Updated the README.md file with Milestone 20 details.

✅ Shared the repository link for submission.

Milestone 21: Address Form Page
✅ Goals:

1️⃣ Frontend - Address Form Page
Created an address form page that collects the following details:

Country
City
Address Line 1
Address Line 2
ZIP Code
Address Type (e.g., Home, Office, etc.)
Implemented a state that stores the address input data for better management.

Ensured that when users click the "Add Address" button on the Profile Page, they are navigated to this form page.

2️⃣ Enhancing User Experience
Designed the address form to be user-friendly and intuitive.
Ensured clear input labels and proper validation for required fields.
3️⃣ Submission Steps
✅ Pushed the updated code to the GitHub repository.
✅ Updated the README.md file with Milestone 21 details.
✅ Shared the repository link for submission.
Milestone 22: Address Storage Endpoint
✅ Goals:

1️⃣ Backend - Address Storage Endpoint
Created an API endpoint that receives address data from the frontend address form.
Added logic to store the received address inside the address array within the user's profile collection in the database.
Ensured endpoint security by restricting access to authenticated users only.
2️⃣ Enhancing User Experience
Ensured proper error handling to manage invalid data entries.
Implemented success and error response messages for clear user feedback.
3️⃣ Submission Steps
✅ Pushed the updated code to the GitHub repository.
✅ Updated the README.md file with Milestone 22 details.
✅ Shared the repository link for submission.


Milestone 23: Address Selection and Order Functionality
What Was Achieved in This Milestone
In Milestone 23, we focused on adding the "Place Order" functionality, allowing users to select a delivery address and place an order. The changes made were crucial to the checkout flow of the e-commerce application. The tasks completed include:

Key Features Implemented:
Place Order Button:

A "Place Order" button was added inside the cart page.

This button navigates users to the Select Address Page where they can choose a delivery address for their order.

Select Address Page:

Created a Select Address Page that displays a list of all addresses linked to the user's profile.

Users can choose one of their saved addresses as the delivery address for the order.

The page ensures a smooth user experience by allowing them to select an address and move forward with the order placement.

Backend Endpoint for Address Retrieval:

A new backend endpoint was written that fetches all saved addresses of the authenticated user from the database.

This endpoint sends the addresses to the frontend, ensuring users can see all their stored addresses when selecting a delivery address.

MongoDB Schema for Orders:

Designed and implemented a Mongoose schema to handle the creation of orders in the backend.

The schema allows for storing order details, including the selected address, products, and user information.

Orders are associated with users, enabling us to track and manage their orders effectively.

Milestone 24: Order Confirmation Page
What Was Achieved in This Milestone
In this milestone, we implemented the Order Confirmation Page in the frontend of our eCommerce application. The page includes:

✅ Displaying all the products being ordered.
✅ Showing the address selected by the user for delivery.
✅ Calculating and displaying the total order value.
✅ Adding a Place Order button to finalize the purchase.

Implementation Details
Used React state management to fetch and display order details.

Ensured the user-selected address is dynamically updated on the confirmation page.

Styled the page using Tailwind CSS for a clean UI.

Implemented logic to calculate and display the total price of the cart.

Integrated the Place Order button with a handler function to proceed with the order.


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