# 🎓 Edemy - Learning Management System (LMS)

Edemy is a full-featured Learning Management System built using the **MERN stack**. It empowers instructors to create and manage courses while giving students a smooth learning experience through enrollment, video lectures, and progress tracking.

---

## 🌐 Live Demo

🚀 [Explore Edemy on Vercel](https://lms-frontend-sigma-two.vercel.app/)

---

## 📁 Repository Structure

LMS/
├── client # Frontend - React + Vite
└── server # Backend - Express + Node.js

markdown
Copy
Edit

---

## ⚙️ Tech Stack

### 🖥️ Frontend
- **React.js** (Vite)
- **Tailwind CSS** (UI styling)
- **Axios** (API calls)
- **React Router DOM** (routing)
- **React Toastify** (notifications)
- **Framer Motion** (animations)
- **React Quill** (rich text editor)
- **RC Progress** (progress bar)
- **React YouTube** (video support)
- **Clerk** (authentication)

### 🛠️ Backend
- **Node.js + Express**
- **MongoDB + Mongoose**
- **Stripe** (payment integration)
- **Cloudinary** (media storage)
- **Multer** (file uploads)
- **CORS, Dotenv, Nodemon** (utilities)

---

## 🚀 Features

- ✅ Secure User Authentication (via Clerk)
- ✅ Instructor Dashboard for managing courses
- ✅ Student Dashboard for tracking progress
- ✅ Video/Image Lecture Uploads
- ✅ Course Enrollment & Progress Tracking
- ✅ Stripe Integration for Payments
- ✅ Mobile-Responsive & Modern UI

---

## 📦 Installation & Setup

### 1. Clone the Repository

```bash
git clone https://github.com/MayurRajRajput/LMS.git
cd LMS
2. Setup Backend
bash
Copy
Edit
cd server
npm install
# Create a .env file based on the template
npm run dev
3. Setup Frontend
bash
Copy
Edit
cd ../client
npm install
# Set environment variables for Clerk, Stripe, etc.
npm run dev
🔐 Environment Variables
📁 Server .env
env
Copy
Edit
PORT=5000
MONGODB_URI=your_mongo_connection_string
STRIPE_SECRET_KEY=your_stripe_secret_key
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
📁 Client .env
env
Copy
Edit
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_key
VITE_STRIPE_PUBLISHABLE_KEY=your_stripe_key
VITE_BACKEND_URL=http://localhost:5000
📸 Screenshots
Add screenshots or screen recordings of the platform here to showcase features and UI.

👨‍💻 Author
Made with ❤️ by Mayur Rajput
Feel free to connect and explore more of my work!

📄 License
Licensed under the MIT License

🌟 Show your support
If you found this project helpful, consider giving it a ⭐ on GitHub and sharing it with others!

vbnet
Copy
Edit

This version is complete with all the sections: live demo, repository structure, tech stack, installation, environ
