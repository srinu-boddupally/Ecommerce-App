# FOREVER — Full Stack MERN E-commerce Platform

FOREVER is a modern full stack E-commerce application built using the MERN Stack. The platform delivers a complete online shopping experience with secure authentication, dynamic product management, cart and order functionality, online payment integration, and a dedicated admin dashboard for managing products and customer orders.

The project focuses on real-world full stack development concepts including REST APIs, JWT authentication, MongoDB integration, payment gateway workflows, image uploads, protected routes, responsive UI design, and cloud deployment.

---

# 🌐 Live Demo

### 🛍 Frontend
https://foreverstyle.vercel.app/

### ⚙️ Admin Dashboard
https://foreverstyle-admin.vercel.app/

---

# ✨ Core Features

## 👤 User Features

- Secure User Signup & Login
- JWT Authentication & Authorization
- Browse Products by Categories
- Search & Filter Products
- Add Products to Cart
- Update Cart Quantity
- Place Orders
- View Order History
- Responsive Modern UI
- Real-Time Product Rendering

---

## 💳 Payment Features

- Stripe Payment Gateway Integration
- Razorpay Payment Gateway Integration
- Cash on Delivery (COD)
- Secure Payment Verification Workflow

---

## 🛠 Admin Dashboard Features

- Admin Authentication
- Add New Products
- Upload Product Images
- List & Manage Products
- Delete Products
- Order Management System
- Update Delivery Status
- Inventory Management

---

# 🛠 Tech Stack

| Category | Technologies |
|----------|--------------|
| Frontend | React.js, Tailwind CSS |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| Authentication | JWT Authentication |
| Payments | Stripe, Razorpay |
| Media Storage | Cloudinary |
| State Management | React Context API |
| API Handling | Axios |
| Deployment | Vercel |
| Version Control | Git & GitHub |

---

# 📁 Project Structure

```bash
ECOMMERCE-APP/
├── admin/                 # Admin Dashboard
├── backend/               # Express Backend APIs
├── frontend/              # React Frontend
├── .gitignore
└── README.md
```

---

# ⚙️ Installation & Setup

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/srinu-boddupally/ECOMMERCE-APP.git

cd ECOMMERCE-APP
```

---

## 2️⃣ Install Dependencies

### Frontend

```bash
cd frontend
npm install
```

### Backend

```bash
cd backend
npm install
```

### Admin Panel

```bash
cd admin
npm install
```

---

## 3️⃣ Configure Environment Variables

Create a `.env` file inside the `backend` folder.

```env
MONGODB_URI=your_mongodb_uri

JWT_SECRET=your_jwt_secret

ADMIN_EMAIL=your_admin_email
ADMIN_PASSWORD=your_admin_password

CLOUDINARY_NAME=your_cloudinary_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_SECRET_KEY=your_cloudinary_secret_key

STRIPE_SECRET_KEY=your_stripe_secret_key

RAZORPAY_KEY_ID=your_razorpay_key_id
RAZORPAY_KEY_SECRET=your_razorpay_key_secret
```

---

# ▶️ Run the Application

## Backend Server

```bash
cd backend
npm run server
```

## Frontend

```bash
cd frontend
npm run dev
```

## Admin Dashboard

```bash
cd admin
npm run dev
```

---

# 🌐 Local Development URLs

| Service | URL |
|----------|------|
| Frontend | http://localhost:5173 |
| Admin Panel | http://localhost:5174 |
| Backend | http://localhost:4000 |

---

# 📸 Main Application Modules

- Home Page
- Product Collections
- Product Details
- Cart Management
- Place Order Page
- Stripe Checkout
- Razorpay Checkout
- User Orders Page
- Admin Dashboard
- Product Management
- Order Management

---

# 🔐 Authentication & Security

- JWT Token Authentication
- Protected User Routes
- Admin Authorization Middleware
- Secure REST APIs
- Form Validation
- Secure Payment Handling

---

# ☁️ Deployment

The application is deployed using modern cloud deployment services.

| Service | Platform |
|----------|-----------|
| Frontend | Vercel |
| Admin Panel | Vercel |
| Backend API | Vercel |
| Database | MongoDB Atlas |
| Image Hosting | Cloudinary |

---

# 📚 Key Learning Outcomes

- Full Stack MERN Development
- REST API Architecture
- MongoDB Database Integration
- JWT Authentication Workflow
- Payment Gateway Integration
- Admin Dashboard Development
- Cloudinary Media Uploads
- Deployment & Hosting
- Responsive UI Development
- Form Validation & Error Handling

---

# 🤝 Contributing

Contributions are welcome.

```bash
Fork the repository

Create your feature branch
git checkout -b feature-name

Commit your changes
git commit -m "Added new feature"

Push to GitHub
git push origin feature-name

Create a Pull Request
