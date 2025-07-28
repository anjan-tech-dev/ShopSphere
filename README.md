🛒 ShopSphere
ShopSphere is a full-stack e-commerce platform featuring a modern frontend, an intuitive admin panel, and a powerful backend API.
This project allows users to browse products with filters, place orders, and log in. Admins can manage inventory and view all orders.

User Interface:

<img width="1798" height="645" alt="image" src="https://github.com/user-attachments/assets/99d91c34-82ae-4c9e-89e5-d27a545f7cea" />

<img width="1896" height="830" alt="image" src="https://github.com/user-attachments/assets/4277cc96-f25d-4c19-bf64-31761b2dc14f" />

<img width="1832" height="816" alt="image" src="https://github.com/user-attachments/assets/84f41364-7c7f-41af-b68b-d980b6c2a049" />

<img width="1882" height="799" alt="image" src="https://github.com/user-attachments/assets/6b338c0c-363f-42fe-a3b5-339543c4ccae" />

<img width="1856" height="815" alt="image" src="https://github.com/user-attachments/assets/51789e53-2aac-4113-b228-90096e62960b" />

<img width="1797" height="877" alt="image" src="https://github.com/user-attachments/assets/1e4b1416-306a-4e58-8ded-bbbb4e9c890a" />

<img width="1866" height="828" alt="image" src="https://github.com/user-attachments/assets/78133b96-c3d8-4882-8eee-d3726cee66ca" />

<img width="1914" height="795" alt="image" src="https://github.com/user-attachments/assets/b89eab65-f4d9-4a20-9e71-b79027156730" />

<img width="1915" height="672" alt="image" src="https://github.com/user-attachments/assets/4846d37b-32fc-4ea4-9a86-c55ce563cb73" />

Admin Panel:

<img width="1167" height="586" alt="image" src="https://github.com/user-attachments/assets/5b65f149-833b-49a2-86fe-8ee6cb36056d" />

<img width="1849" height="838" alt="image" src="https://github.com/user-attachments/assets/9131be81-bd7d-4aa1-b71c-1279b9a59fd7" />

<img width="1852" height="387" alt="image" src="https://github.com/user-attachments/assets/69e88f16-3e67-4682-b278-680e4f9592c5" />

<img width="1919" height="489" alt="image" src="https://github.com/user-attachments/assets/0439ce82-bebf-405a-ae8b-79366011fcc3" />





📁 Project Structure
bash
Copy
Edit
ShopSphere/
│
├── admin/             # Frontend 
├── backend/              # Admin panel 
└── frontend/             # Backend 


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
Deploy frontend/ and admin/ folders on Vercel

Backend
Deploy backend on Railway


Deploy server/ on Railway

Make sure your environment variables are set on Railway dashboard

🙌 Contribution
Pull requests are welcome. For major changes, please open an issue first.
