[README.md](https://github.com/user-attachments/files/25746626/README.md)
# 💸 Expense Tracker

An interactive, full-stack Expense Tracker web application with **user authentication, income and expense management, file uploads, and dashboard analytics**. Built with **MERN stack** and deployed using **Render** and **Vercel**.

---

## 🚀 **Live Demo**

🔗 **Frontend**: [Expense Tracker Frontend](https://expense-tracker-683i.vercel.app)  
🔗 **Backend API**: [Expense Tracker Backend](https://expense-tracker-backend-82la.onrender.com)

---

## 🔑 **Test Login Credentials**

> Use the below credentials to log in and test the application:

- **Email**: `sathwikreddys467@gmail.com`  
- **Password**: `Sathwik@123`

---

## 📂 **Project Structure**

Expense_Tracker/
├── client/ # React frontend (Vite)<br>
│ ├── src/ <br>
│ └── vite.config.js <br>
├── server/ # Node.js + Express backend <br>
│ ├── controllers/ <br>
│ ├── models/ <br> 
│ ├── routes/ <br>
│ ├── middleware/ <br>
│ ├── config/ <br>
│ └── server.js <br>
└── README.md <br>

---

## ⚙️ **Tech Stack**

- **Frontend**: React.js, Axios, Context API, Vite
- **Backend**: Node.js, Express.js, MongoDB, Mongoose, JWT
- **Authentication**: JWT-based secure auth
- **File Uploads**: Multer for image uploads
- **Deployment**: Render (Backend), Vercel (Frontend)
- **Miscellaneous**: dotenv for environment variables, cors for cross-origin requests

---

## ✨ **Features**

✅ User registration with email OTP verification  
✅ JWT-based login authentication  
✅ Add, view, and delete income and expense transactions  
✅ Upload profile images and store on backend  
✅ Download income and expense data as Excel files  
✅ Dashboard summary with total balance, income, and expenses  
✅ Protected routes with middleware  
✅ Fully deployed with HTTPS

---

## 📝 **Setup Instructions**

### 🔧 **1. Clone the repository**


git clone https://github.com/sathwik789/Expense_Tracker.git
cd Expense_Tracker

⚙️ 2. Setup Backend
cd server
npm install
Create a .env file inside server directory:

PORT=8000 <br>
MONGO_URL=your_mongodb_connection_string <br>
JWT_SECRET=your_jwt_secret <br>
CLIENT_URL=https://your-frontend-url.vercel.app <br>
EMAIL_HOST=smtp.gmail.com <br>
EMAIL_PORT=587 <br>
EMAIL_USER=your_email@gmail.com <br>
EMAIL_PASS=your_email_password_or_app_password <br>
Start backend: 
npm start

⚛️ 3. Setup Frontend

cd client
npm install

Create a .env file inside client directory:
VITE_API_URL=https://your-backend-url.onrender.com/api/v1

Start frontend:
npm run dev

🌐 Deployment
🚀 Frontend (Vercel)
Push your client folder to a separate GitHub repository (if deploying standalone).

Connect repository in Vercel dashboard.

Set environment variable VITE_API_URL to your Render backend URL.

🚀 Backend (Render)
Create new Web Service in Render.

Connect your backend repository.

Add environment variables as in .env.

Deploy.

🐛 Common Issues
❌ CORS errors: Ensure your backend CLIENT_URL matches frontend deployed URL.
❌ Mixed Content errors: Always use HTTPS URLs for images and APIs in production.
❌ MongoDB connection errors: Check IP access and connection string in Atlas.

🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

📝 License
This project is licensed under the MIT License.

✉️ Contact
Sathwik Reddy
📧 reddysathwik019@gmail.com
🔗 LinkedIn

