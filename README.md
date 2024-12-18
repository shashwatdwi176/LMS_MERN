# 🚀 Learning Management System (LMS)  

A full-stack Learning Management System built using the **MERN stack** with course management, user authentication, secure payments, and file uploads.  

---

## 📋 Features  

- **User Authentication**: JWT-based secure login/signup.  
- **Role-Based Access Control**: Separate user roles for Admin and Students.  
- **Course Management**: Add, edit, delete, publish, and unpublish courses.  
- **File Uploads**:  
   - **Multer** for file handling.  
   - **Cloudinary** for secure video and image storage.  
- **Stripe Integration**: Secure course payments with Stripe and webhooks.  
- **Progress Tracking**: Track purchased course progress.  
- **Search & Filter**: Search and categorize courses.  
- **Dark/Light Mode**: Switch between themes for better UX.  

---

## 🛠️ Tech Stack  

**Frontend**  
- React.js  
- Redux Toolkit (RTK Query)  
- React Router DOM  
- Shadcn UI  

**Backend**  
- Node.js  
- Express.js  
- MongoDB  
- Multer (File Uploads)  
- Cloudinary (File Storage)  
- Stripe (Payment Integration)  

---

## 📁 Project Structure  

📦 LMS
├── client # React.js frontend
├── server # Node.js backend
│ ├── models # MongoDB Models
│ ├── controllers # Backend Logic for Routes
│ ├── routes # API Endpoints
│ ├── middlewares # Authentication & Role Protection
│ └── utils # Utility Functions
└── README.md # Project Documentation

Backend Setup

Navigate to the server folder:
bash
Copy code
cd server
Install dependencies:
bash
Copy code
npm install
Create a .env file and add:
env
Copy code
PORT=5000  
MONGO_URI=your_mongodb_connection_string  
JWT_SECRET=your_jwt_secret  
STRIPE_SECRET=your_stripe_secret_key  
CLOUDINARY_CLOUD_NAME=your_cloud_name  
CLOUDINARY_API_KEY=your_api_key  
CLOUDINARY_API_SECRET=your_api_secret  
Start the backend server:
bash
Copy code
npm run dev
Frontend Setup

Navigate to the client folder:
bash
Copy code
cd ../client
Install dependencies:
bash
Copy code
npm install
Start the React development server:
bash
Copy code
npm start
