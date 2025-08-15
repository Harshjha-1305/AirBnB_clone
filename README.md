# 🏡 Airbnb Clone

A full-stack **Airbnb clone** built with the **MERN stack** following the **MVC (Model-View-Controller)** architecture.  
The app allows users to explore listings, view property details, and simulate booking experiences — inspired by the real Airbnb platform.  

🚀 **Live Demo:** [https://airbnb-clone-jyq0.onrender.com/](https://airbnb-clone-jyq0.onrender.com/)

---

## 📌 Features

- 🏠 Browse and search property listings
- 📸 Upload property images
- 👤 User authentication & authorization
- 📅 Booking simulation
- 💾 Data stored in **MongoDB Atlas**
- 🖥️ Fully responsive UI

---

## 🛠 Tech Stack

### **Frontend**
- React.js
- Axios
- Bootstrap / Tailwind CSS (if applicable)

### **Backend**
- Node.js
- Express.js
- MVC architecture

### **Database**
- MongoDB Atlas (cloud-based MongoDB)

### **Deployment**
- Render (Backend + Frontend)

---

## 📂 Project Structure (MVC)
├── models # Mongoose models for MongoDB
├── views # Frontend templates or React build
├── controllers # Request handling logic
├── routes # Express route definitions
├── public # Static assets
└── server.js # App entry point


---

## ⚙️ Installation & Setup

1. **Clone the repository**
   
   git clone [<your-repo-url>](https://github.com/Harshjha-1305/AirBnB_clone)
   cd airbnb-clone
   
2.  **Install dependencies**
   
  npm install
  cd client && npm install
  cd ..
  
3. **Create a .env file in the root folder**

  MONGO_URI=<your-mongodb-atlas-uri>
  JWT_SECRET=<your-secret>
  PORT=5000
  
4. **Run the app locally**

  # Start backend
  npm run dev
  
  # Start frontend
  cd client && npm start
  Visit:
   http://localhost:3000
   

## 📸 Screenshot

<img width="1869" height="909" alt="Screenshot 2025-08-15 102939" src="https://github.com/user-attachments/assets/b963be24-c615-400c-abd4-81b61a202c43" />


## 🤝 Contributing
Pull requests are welcome!
For major changes, please open an issue first to discuss what you’d like to change.

## 📜 License
This project is licensed under the MIT License — see the LICENSE file for details
