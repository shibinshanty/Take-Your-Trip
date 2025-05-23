

# Tour Management System

This is a full-stack **Tour Management System** project built using:

- **Frontend**: React (in the `frontend` folder)
- **Backend**: Node.js with Express and MongoDB (in the `backend` folder)

---

## 🌐 Project Structure
tour-management/
│
├── frontend/ # React application for user interface
│
├── backend/ # Node.js backend with Express and MongoDB
│
└── README.md


---

## 🚀 Features

- User registration and authentication (can be extended with OTP)
- Manage tours (create, update, delete)
- Tour booking and availability
- Dashboard or admin panel (optional)
- Responsive design (using Tailwind CSS or similar)

---

## 🛠 Tech Stack

### Frontend:
- Vite + React
- React Router
- Tailwind CSS (optional)
- Axios


### Backend:
- Node.js
- Express.js
- MongoDB (with Mongoose)
- JWT for Authentication (optional)
- Nodemailer/Twilio for OTP (optional)

---

## ⚙️ Getting Started

### Prerequisites

- Node.js and npm installed


### Clone the repo

>git clone https://github.com/shibinshanty/Take-Your-Trip
>cd tour-management

##Backend setup

cd backend
npm install
# Create a .env file with your environment variables (PORT,DB, JWT_SECRET,EMAIL_USER,EMAIL_PASS, RAZORPAY_KEY_ID, RAZORPAY_KEY_SECRET)
npm run dev


##Frontend setup
cd frontend
npm install
npm run dev


