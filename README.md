# 💬 ChatSphere

ChatSphere is a real-time chat application built with the **MERN stack (MongoDB, Express.js, React, Node.js)** that supports multilingual communication through automatic message translation. It enables users from different linguistic backgrounds to chat seamlessly and instantly.

---

## 🚀 Features

- 🔁 Real-time messaging using Socket.IO  
- 🌍 Automatic language translation via Microsoft Azure Translator API  
- 🧠 State management with Zustand  
- 🖼️ Image upload and delivery via Cloudinary  
- 🔐 Secure user authentication with JWT  
- 🌙 Responsive UI with Tailwind CSS and DaisyUI  
- 📱 Optimized for both desktop and mobile  

---

## 🛠️ Tech Stack

### Frontend
- React.js  
- Tailwind CSS + DaisyUI  
- Zustand  
- Socket.IO Client  
- React Router DOM  

### Backend
- Node.js  
- Express.js  
- MongoDB with Mongoose  
- Socket.IO  
- JWT Authentication  
- Cloudinary  
- Microsoft Azure Translator API  

---

# 📦 Installation & Setup

## 🔹 Prerequisites

Make sure you have:

- Node.js (v18 or above)
- MongoDB (Local or Atlas)
- Azure Translator API Key
- Cloudinary Account

---

## 1️⃣ Clone the Repository

```bash
git clone https://github.com/your-username/ChatSphere.git
cd ChatSphere
```

---

## 2️⃣ Install Dependencies and Run the Application

### Backend

```bash
cd backend
npm install
npm run dev
```

### Frontend

```bash
cd frontend
npm install
npm run dev
```

---

## 3️⃣ Environment Variables Setup

Create a `.env` file inside the **server** folder:

```env
PORT=5000
MONGO_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret

CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret

AZURE_TRANSLATOR_KEY=your_azure_key
AZURE_TRANSLATOR_ENDPOINT=https://api.cognitive.microsofttranslator.com/
AZURE_TRANSLATOR_REGION=your_region
```

---


# 📜 License

This project is licensed under the MIT License.


---

# 👨‍💻 Author

**Tanveer MK**

If you like this project, consider giving it a ⭐ on GitHub!
