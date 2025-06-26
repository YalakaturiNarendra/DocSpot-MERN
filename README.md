# 🩺 DocSpot: Online Appointment Booking System
DocSpot is a full-stack MERN (MongoDB, Express.js, React, Node.js) application that facilitates online appointment booking between patients and doctors. It provides distinct dashboards for Patients, Doctors, and Admins, enabling seamless medical appointment management.

# Features
User Authentication – Secure registration and login for Patients, Doctors, and Admins.

Role-Based Access Control – Different functionalities and dashboards based on user roles.

Doctor Management (Admin) – Approve or reject new doctor registrations.

Doctor Directory (Patient) – View approved doctors with specialties and locations.

Appointment Booking (Patient) – Book appointments with available doctors.

Appointment Management (Doctor) – View requests, update statuses, and add notes.

Appointment History (Patient) – View upcoming and past appointments.

Backend Validation & Error Handling – Robust API endpoints with proper error responses

# 🚀 Technologies Used

  🔧 Backend
  Node.js

  Express.js

  MongoDB (with Mongoose ODM)

  JWT (JSON Web Tokens) for authentication

  bcryptjs for password hashing

  CORS

  dotenv

  🎨 Frontend
React.js

Material-UI (MUI) for UI components

Tailwind CSS for utility-first styling

Axios for API requests

React Router DOM for navigation

React Context API for state management

🛢️ Database
MongoDB Atlas (Cloud Database)

☁️ Deployment
Render (for both Frontend Static Site and Backend Web Service)

# 🌐 Deployed Application
Access the live application here:
https://docspot-frontend-sk5s.onrender.com

🔑 Sample Credentials

👑 Admin

Email: admin@gmail.com

Password: admin123

Dashboard: /admin-dashboard

Note: This account has permissions to approve/reject doctor registrations.

🧑‍⚕️ Doctor

Email: doctor1@gmail.com

Password: password123

Dashboard: /doctor-dashboard

Note: Can view appointments and update statuses.

👤 Patient

Email: patient1@gmail.com

Password: password123

Dashboard: /user-dashboard

Note: Can book appointments and view upcoming history.

# 🛠️ Local Setup Instructions

✅ Prerequisites

Node.js

npm

MongoDB (Local or Atlas)

# Clone the Repository

git clone https://github.com/YalakaturiNarendra/DocSpot-MERN.git

cd DocSpot-MERN

# Backend Setup

cd server

npm install

# Create a .env file in the server/ directory:

PORT=5000
NODE_ENV=development
MONGO_URI=mongodb://localhost:27017/docspotdb

OR for Atlas:

MONGO_URI=mongodb+srv://<username>:<password>@<cluster-url>/docspotdb?retryWrites=true&w=majority

JWT_SECRET=your_secret_key
CORS_ORIGIN=http://localhost:3000

# Start the backend server:

node server.js

# Frontend Setup

cd client

npm install

npm start

Frontend runs at: http://localhost:3000

# 🤝 Contributing

Feel free to fork, improve, and submit a PR.

# 📝 License

Licensed under the MIT License
