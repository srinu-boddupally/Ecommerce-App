# FOREVER - Full Stack E-commerce Application

FOREVER is a modern full stack E-commerce web application built using the MERN Stack. The project includes user authentication, dynamic product management, cart and order functionality, online payment integration, and a separate admin dashboard for managing products and orders.

The application is designed with a clean and responsive UI inspired by modern fashion E-commerce platforms and focuses on real-world full stack development concepts including REST APIs, authentication, database integration, payment gateways, and admin management.

---

# ✨ Features

## 👤 User Features
- User Signup & Login Authentication
- JWT-based Authorization
- Browse Products by Categories
- Search Products
- Add to Cart
- Update Cart Quantity
- Place Orders
- View My Orders
- Responsive UI Design

---

## 💳 Payment Integration
- Stripe Payment Gateway Integration
- Razorpay Payment Gateway Integration
- Cash on Delivery (COD)
- Payment Verification Flow

---

## 🛠 Admin Features
- Admin Login
- Add New Products
- Upload Product Images
- List All Products
- Delete Products
- Manage Orders
- Update Order Status

---

# 🛠 Tech Stack

| Layer | Tech Used |
|------|------|
| Frontend | React.js, Tailwind CSS |
| Backend | Node.js, Express.js |
| Database | MongoDB |
| Authentication | JWT Authentication |
| Payment Gateway | Stripe, Razorpay |
| Image Storage | Cloudinary |
| State Management | React Context API |
| HTTP Client | Axios |
| Deployment | Vercel / Render |
| Version Control | Git & GitHub |

---

# 📁 Folder Structure

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

## 1. Clone Repository

```bash
git clone https://github.com/your-username/ECOMMERCE-APP.git

cd ECOMMERCE-APP
```

---

## 2. Install Dependencies

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

## 3. Setup Environment Variables

Create a `.env` file inside backend folder.

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

# ▶️ Run the Project

## Backend

```bash
cd backend
npm run server
```

## Frontend

```bash
cd frontend
npm run dev
```

## Admin Panel

```bash
cd admin
npm run dev
```

---

# 🌐 Local Development URLs

| Service | URL |
|------|------|
| Frontend | http://localhost:5173 |
| Admin Panel | http://localhost:5174 |
| Backend | http://localhost:4000 |

---

# 📸 Main Modules

- Home Page
- Product Collection
- Product Details
- Cart Page
- Place Order Page
- Stripe Checkout
- Razorpay Checkout
- My Orders Page
- Admin Dashboard
- Product Management
- Order Management

---

# 🔐 Authentication

- JWT Token Authentication
- Protected Routes
- Admin Authorization Middleware
- Secure API Access

---

# 🚀 Deployment

The project can be deployed using:

- Frontend → Vercel
- Backend → Render / Railway
- Database → MongoDB Atlas
- Admin Panel → Vercel

---

# 📚 What I Learned

- Full Stack MERN Development
- REST API Design
- MongoDB Database Operations
- JWT Authentication
- Payment Gateway Integration
- Admin Dashboard Architecture
- State Management with Context API
- Cloudinary Image Upload
- Deployment Workflow

---

# 🤝 Contributing

Contributions are welcome.

```bash
Fork the repository
Create your feature branch
Commit your changes
Push to the branch
Create a Pull Request
```

---


