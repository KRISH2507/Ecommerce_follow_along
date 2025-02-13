📌 Project Name: E_Commerce_Follow_Along

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

Milestone 7: User Login Authentication

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

Complied with security standards like GDPR and PCI-DSS.

README Update:

Documented progress for Milestone 6 and updated the repository.

Milestone 7: User Login Authentication

✅ Goals:

Created Login Endpoint:

Developed an API endpoint to accept user credentials (email/username and password).

Retrieved the corresponding user from the database based on the provided credentials.

Handled errors if the user does not exist.

Password Validation:

Used bcrypt to compare the entered password with the stored hashed password.

Ensured a secure authentication process without decrypting passwords.

Authentication Response:

Successfully authenticated users receive an access token for session management.

Invalid credentials return an error message.

Security Considerations:

Implemented proper error handling to avoid leaking sensitive information.

Used best practices for password security and hashing.

README Update:

Documented progress for Milestone 7 and updated the repository.

▶ How to Run the Project

Clone the repository:

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

🚀 Next Steps

Implement session-based authentication and user roles.

Add JWT-based authentication for secure API calls.

Improve frontend UI for login and registration.

Optimize database queries for better performance.

👥 Contributing

Contributions are welcome! Feel free to fork this repository and submit pull requests.

🏆 License

This project is licensed under the MIT License.

