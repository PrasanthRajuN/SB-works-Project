# SB Works - Freelancing Platform

## 📌 Project Title
**SB Works - A MERN Stack Freelancing Platform**

---

## 📄 Brief Description / Introduction

SB Works is a full-stack freelancing platform that connects clients with skilled freelancers. The platform enables clients to post projects and freelancers to bid, communicate, collaborate, and submit work—all within a secure and intuitive interface.

It includes functionality for:
- Project posting & bidding
- Freelancer profiles
- Client reviews
- Secure real-time messaging
- Admin oversight for platform safety

SB Works is designed to streamline the freelancing process for both clients and freelancers while maintaining quality and security through admin monitoring.

---

## ✨ Features / Functionalities

### 👤 Freelancer Features:
- Register/Login
- Browse available projects
- Submit proposals with portfolio samples
- Real-time chat with clients
- Submit completed work and receive feedback

### 👥 Client Features:
- Register/Login
- Post new projects
- View and evaluate freelancer proposals
- Chat with selected freelancer
- Approve submissions and give feedback

### 🛠️ Admin Features:
- Monitor user activities
- View and manage project data
- Resolve disputes
- Enforce platform policies

---

## ⚙️ Technology Stack (MERN)

- **MongoDB** – NoSQL database for storing users, projects, chats, and proposals
- **Express.js** – Backend framework for building APIs
- **React.js** – Frontend framework for building UI
- **Node.js** – JavaScript runtime for server-side logic

### Additional Libraries Used:
- Axios (API requests)
- Mongoose (MongoDB ODM)
- Bcrypt (Password encryption)
- Bootstrap & Material UI (UI styling)
- CORS (Cross-origin support)

---

## 🛠️ Setup Instructions (Run Locally)

### 1. Clone the Repository

``bash
- git clone https://github.com/PrasanthRajuN/SB-works-Project
cd Freelancer-SBWorks-code

### 2. Install Dependencies
#For Client:

cd client
npm install

#For Server:

cd ../server
npm install
3. Environment Setup
Create a .env file in the server folder and add:

MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
4. Start the Development Servers
Start Backend Server:

cd server
npm start
Start Frontend Server:

cd ../client
npm start
Visit: http://localhost:3000

📁 Project Structure
bash
Copy
EditFreelancer-SBWorks-code/
│
├── client/         # React frontend
│   └── ...
│
├── server/         # Node/Express backend
│   └── ...
│
├── README.md
└── .gitignore

🧾 Documentation
Project details, description, and milestones can be found here.
https://drive.google.com/drive/folders/1usLtfTpsLb8c5-Gd0MLzduCV2nvJ0opa?usp=drive_link

📹 Demonstration Video (Optional)
https://drive.google.com/file/d/1nzsEGZjxvCjo4DLWva8WNY5EWj-7doCa/view?usp=drive_link

