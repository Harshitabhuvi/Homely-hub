# Homely-hub
HomelyHub is a full-stack MERN application for finding, listing, and booking accommodations.
Users can explore properties, book stays, make payments, and manage their profiles easily.

🚀 Tech Stack

Frontend: React.js (Vite), Redux Toolkit, Axios, React Router

Backend: Node.js, Express.js, MongoDB

Others: JWT Auth, Payment Gateway, dotenv

⚙️ Features

🏠 Browse and filter accommodations

💳 Secure booking and payment

👤 User authentication & profile management

🏘️ Host can list and manage properties

📱 Responsive UI design

🧩 Setup Instructions
# Clone repo
git clone https://github.com/<your-username>/HomelyHub.git
cd HomelyHub

# Backend setup
cd Backend
npm install
npm run dev

# Frontend setup
cd ../Frontend
npm install
npm run dev


Create a .env file in Backend with:

PORT=5000
MONGO_URI=your_mongodb_url
JWT_SECRET=your_secret
PAYMENT_KEY=your_payment_key

📂 Folder Structure
HomelyHub/
├── Backend/
│   ├── src/
│   └── .env
├── Frontend/
│   ├── src/
│   ├── public/
│   └── vite.config.js
└── README.md

