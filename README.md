# E_Commerce_Follow_Along

## 🚀 Overview
This project is an e-commerce website developed through a series of milestones, progressively adding features to build a complete and functional application.

## 📚 Table of Contents
- Overview
- Tech Stack
- Milestones
  - Milestone 1: Project Setup
  - Milestone 2: Frontend & Backend Initialization
  - Milestone 3: Backend Structure & Server Setup
  - Milestone 4: Creating User Model and Controller
  - Milestone 5: Sign-Up Page & Form Validation
  - Milestone 6: Secure User Registration
  - Milestone 7: User Login Authentication
  - Milestone 8: Product Model and API
  - Milestone 9: Product Input Form
- How to Run the Project
- Next Steps
- Contributing
- License

## 🛠 Tech Stack
- **Frontend:** React.js, Tailwind CSS
- **Backend:** Node.js, Express.js
- **Database:** MongoDB
- **File Uploads:** Multer
- **Password Encryption:** bcrypt
- **Version Control:** Git, GitHub

## 📌 Milestones

### Milestone 1: Project Setup
✅ **Goals:**
- Created and updated README.md file.
- Initialized GitHub repository for version control.

### Milestone 2: Frontend & Backend Initialization
✅ **Goals:**
- Organized project folder structure with frontend and backend directories.
- Set up a React application for UI development.
- Configured a simple Node.js server with Express.
- Integrated Tailwind CSS for modern styling.
- Developed a basic login page.

### Milestone 3: Backend Structure & Server Setup
✅ **Goals:**
- Organized backend structure (routes, controllers, models, middleware).
- Set up a Node.js and Express.js server.
- Connected MongoDB for data storage.
- Implemented error handling.

### Milestone 4: Creating User Model and Controller
✅ **Goals:**
- Created a user model with attributes like name, email, password, and profile picture.
- Developed user-related API endpoints.
- Integrated Multer for file uploads.

### Milestone 5: Sign-Up Page & Form Validation
✅ **Goals:**
- Designed a user-friendly sign-up form.
- Implemented email and password validation.
- Integrated frontend registration flow with backend API.
- Displayed validation errors in real time.

### Milestone 6: Secure User Registration
✅ **Goals:**
- Used bcrypt to hash passwords.
- Ensured secure password storage.
- Modified user registration endpoint to handle hashing securely.
- Followed security best practices.

### Milestone 7: User Login Authentication
✅ **Goals:**
- Developed a login API endpoint.
- Used bcrypt for secure password validation.
- Implemented authentication response with access tokens.

### Milestone 8: Product Model and API
✅ **Goals:**
- Created a Product model with attributes such as name, description, price, and images.
- Developed API routes for adding and retrieving products.
- Enabled file uploads for product images.
- Integrated validation checks to ensure correct data format.

### Milestone 9: Product Input Form
✅ **Goals:**
- Designed and implemented a frontend form for product input.
- Enabled users to upload multiple product images.
- Ensured all product details (name, description, price, etc.) are captured correctly.
- Connected frontend form submission with backend API.

📌 **Note:** Future improvements can include admin access for product uploads and shop profile-based product management.

## ▶ How to Run the Project

Clone the repository:
```sh
git clone https://github.com/your-username/E_Commerce_Follow_Along.git
cd E_Commerce_Follow_Along
```

Install dependencies for both frontend and backend:
```sh
cd frontend && npm install
cd ../backend && npm install
```

Run the backend server:
```sh
npm start
```

Run the frontend application:
```sh
cd frontend
npm start
```

Open `http://localhost:3000/` in your browser.

## 🚀 Next Steps
- Implement session-based authentication and user roles.
- Add JWT-based authentication for secure API calls.
- Improve frontend UI for login and registration.
- Optimize database queries for better performance.
- Enhance product cards with filtering and sorting features.

## 👥 Contributing
Contributions are welcome! Feel free to fork this repository and submit pull requests.

## 🏆 License
This project is licensed under the MIT License.

