# 🛍️ MERN Clothing Store

A full-stack E-Commerce Clothing Store built using the **MERN Stack** with modern UI powered by **Tailwind CSS**.

This project includes:

- 🛒 Customer Shopping Platform  
- 🔐 Authentication with JWT  
- 🧑‍💼 Admin Dashboard  
- 📦 Product & Order Management  
- ☁️ Cloudinary Image Upload  
- 💳 Razorpay Payment Integration  
- 📱 Responsive Design  

---

## 🚀 Tech Stack

### Frontend (Customer)
- React 18
- Vite
- Tailwind CSS
- React Router DOM
- Axios
- React Toastify

### Admin Panel
- React 18
- Vite
- Tailwind CSS
- Axios
- Order Summary Dashboard
- Product Management

### Backend
- Node.js
- Express.js
- MongoDB (Mongoose)
- JWT Authentication
- Bcrypt
- Multer
- Cloudinary
- Razorpay

---

## 📂 Project Structure

```
online_clothes_store-main/
│
├── backend/
├── frontend/     # Customer Side
├── admin/        # Admin Dashboard
```

---

# ✨ Features

## 👤 User Features

- User Registration & Login
- JWT Authentication
- Add to Cart
- Remove from Cart
- Order Placement
- Order History
- Razorpay Payment Integration
- Responsive UI

---

## 🧑‍💼 Admin Features

- Admin Login
- Add New Products
- Upload Product Images (Cloudinary)
- View Product List
- Delete Products
- View Order Summary
- Manage Orders

> ⚠️ Note: Stripe dependency exists but is NOT used in this project.

---

# 🛠️ Installation & Setup

## 1️⃣ Clone the Repository

```bash
git clone <your-repo-link>
cd online_clothes_store-main
```

---

## 2️⃣ Backend Setup

```bash
cd backend
npm install
```

### Create `.env` file inside backend:

```env
PORT=4000
MONGO_URL=mongodb://127.0.0.1:27017/onlinestore
JWT_SECRET=your_secret_key

CLOUDINARY_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_SECRET_KEY=your_secret_key

RAZORPAY_KEY_ID=your_key_id
RAZORPAY_KEY_SECRET=your_key_secret
```

### Start Backend Server

```bash
npm start
```

Backend runs on:

```
http://localhost:4000
```

---

## 3️⃣ Frontend (Customer) Setup

```bash
cd frontend
npm install
npm run dev
```

Frontend runs on:

```
http://localhost:5173
```

---

## 4️⃣ Admin Panel Setup

```bash
cd admin
npm install
npm run dev
```

Admin runs on:

```
http://localhost:5174
```

---

# 🔐 Authentication

- JWT-based authentication
- Protected routes using middleware
- Admin protected routes
- Tokens stored in localStorage

---

# 🗄️ Database

- MongoDB Local Database
- Collections:
  - users
  - products
  - orders

---

# ☁️ Image Upload

- Images are uploaded using **Multer**
- Stored securely in **Cloudinary**
- URLs saved in MongoDB

---

# 💳 Payment Integration

- Razorpay Integrated
- Order created after successful payment
- Payment verification handled in backend

---

# 🧪 Development Commands

### Backend
```bash
npm start
```

### Frontend
```bash
npm run dev
```

### Admin
```bash
npm run dev
```

---

# 📌 Important Notes

- Make sure MongoDB is running locally.
- Database name should NOT contain `/`
- Clear browser localStorage if JWT errors occur.
- Stripe dependency exists but not implemented.

---

# 📸 Future Improvements

- Implement Stripe payment fully
- Add product search & filters
- Add product ratings & reviews
- Add wishlist feature
- Add inventory tracking
- Deploy to cloud (Render / Vercel)

---

# 👨‍💻 Author

Built using MERN Stack with modern UI design.

---

# 📜 License

This project is for educational and portfolio purposes.