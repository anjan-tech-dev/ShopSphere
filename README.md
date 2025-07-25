🛒 ShopSphere
ShopSphere is a full-stack e-commerce platform featuring a modern frontend, an intuitive admin panel, and a powerful backend API.
This project allows users to browse products with filters, place orders, and log in. Admins can manage inventory and view all orders.

📁 Project Structure
bash
Copy
Edit
ShopSphere/
│
├── admin/             # Frontend (Vercel deployed)
├── backend/              # Admin panel (Vercel deployed)
└── frontend/             # Backend (Railway deployed)


🌐 Live Links
Frontend (User Interface): [Vercel Link](https://shop-sphere-wfqh.vercel.app/)

Admin Panel: [Vercel Link](https://shop-sphere-cuwf.vercel.app/)

Backend API: [Railway Link](https://shopsphere-production-61e6.up.railway.app/)

✨ Features
🧑‍💼 Admin Panel
Secure login

View all orders

Add / Edit / Delete items

View user details

🛍️ User Frontend
Product filters

Add to cart

Place orders

Login / Signup

Product images via Cloudinary

🔧 Backend (Node.js + Express + MongoDB)
REST API for products, users, and orders

JWT-based Authentication

Cloudinary image upload integration

MongoDB Atlas for database

Hosted on Railway

⚙️ Tech Stack
Layer	Technology
Frontend	React, Vite, Tailwind CSS
Admin Panel	React, Vite, Tailwind CSS
Backend	Node.js, Express, MongoDB
Storage	Cloudinary (for images)
Auth	JWT
Hosting	Vercel (Frontend & Admin)
API Hosting	Railway

🚀 Getting Started (Development)
Prerequisites
Node.js and npm

MongoDB Atlas or Local MongoDB

Cloudinary account

Installation
bash
Copy
Edit
git clone https://github.com/anjan-tech-dev/shopshere.git
cd shopshere
Install dependencies:
bash
Copy
Edit
cd server
npm install

cd ../client
npm install

cd ../admin
npm install
Environment Variables
Create a .env file in server/:

env
Copy
Edit
PORT=5000
MONGO_URI=your_mongo_uri
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
🛠 Deployment
Frontend & Admin
Deploy client/ and admin/ folders on Vercel

Backend
Deploy server/ on Railway

Make sure your environment variables are set on Railway dashboard

🙌 Contribution
Pull requests are welcome. For major changes, please open an issue first.
