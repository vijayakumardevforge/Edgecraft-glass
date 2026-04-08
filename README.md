# 🏢 Edgecraft Glass Platform  
Developed by **Vijayakumar**

A full-stack web application for customizing and ordering premium glass products, designed with a modern UI and seamless user experience.

---

## 🚀 Features

- 🔐 User Authentication – Secure login and registration using JWT  
- 🪟 Custom Glass Ordering – Dynamic size selection with real-time price calculation  
- 🖥️ Modern UI – Responsive and user-friendly design  
- 🎁 Gift Products Section – Browse and purchase glass-based gift products  
- 🛒 Shopping Cart – Add, update, and remove items  
- 💳 Payment Integration – UI and workflow implemented, backend integration in progress  
- 📦 Order Management – Track orders and history  
- ⭐ Review System – Rating and feedback feature  

---

## 📱 Screens

### 1. Login Page  
<img src="https://github.com/user-attachments/assets/fdd3c019-cadd-418e-9cbe-5900618a8ed3" width="500"/>

### 2. Product Listing Page  
<img src="https://github.com/user-attachments/assets/198abb19-5dfa-4653-9859-4a41b209ed6d" width="500"/>

### 3. Product Details & Customization  
<img src="https://github.com/user-attachments/assets/da7d922a-d1d3-467c-ae83-27faf27832fa" width="500"/>

### 4. Gift Products Page  
<img src="https://github.com/user-attachments/assets/48af44ef-cb6b-4d46-ae7b-087a39bf61a6" width="500"/>

### 5. Cart Page  
<img src="https://github.com/user-attachments/assets/033e7396-8042-4b1c-b45a-ad753339b752" width="500"/>

### 6. Payment Page  
<img src="https://github.com/user-attachments/assets/19ae6121-37b6-4050-9cec-e9854b32a24d" width="500"/>

### 7. Order Confirmation Page  
<img src="https://github.com/user-attachments/assets/9b817610-7b5e-4715-b600-82d5d2081fd6" width="500"/>

### 8. Orders Page  
<img src="https://github.com/user-attachments/assets/a2db8bbb-ff99-4cbb-bb9b-e4e11a7aaa53" width="500"/>

### 9. Review Page  
<img src="https://github.com/user-attachments/assets/615d2957-1eaf-4b43-9822-1d5196ef3898" width="500"/>

---

## 🛠️ Technologies Used

**Frontend**
- React  
- TypeScript  
- Tailwind CSS  

**Backend**
- Python (Flask)  
- JWT Authentication  

**Database**
- MongoDB  

---

## ⚙️ Setup Instructions

### Install Dependencies

Frontend:
```bash
npm install
```

Backend:
```bash
cd backend
pip install -r requirements.txt
```

---

### Run Project

Full:
```bash
npm run dev:full
```

Frontend:
```bash
npm run dev
```

Backend:
```bash
cd backend
python app.py
```

---

### Environment Variables

Frontend (.env):
```
VITE_API_URL=http://localhost:5000/api
```

Backend (.env):
```
SECRET_KEY=your-secret-key
JWT_SECRET_KEY=your-jwt-secret-key
MONGODB_URI=mongodb://localhost:27017/
MONGODB_DB_NAME=edgecraft_glass
FLASK_ENV=development
```

---

## 🗄️ Database Collections

- users  
- orders  
- reviews  

---

## 📌 API Endpoints

- POST /api/register  
- POST /api/login  
- GET /api/profile  
- POST /api/orders  
- GET /api/orders  
- POST /api/payment/process  
- POST /api/reviews  

---

## 🔮 Future Improvements

- 💳 Complete payment gateway integration  
- 📦 Real-time order tracking  
- 📱 Mobile app version  
- 🔔 Notifications system  

---

## 📌 Getting Started

Make sure MongoDB is running locally or use MongoDB Atlas.
