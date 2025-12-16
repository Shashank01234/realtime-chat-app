# 💬ECHO (Realtime Chat Application) 

A full-stack real-time chat application that enables users to sign up, log in securely, chat instantly, share images, and manage contacts — built with modern web technologies for speed, scalability, and a clean user experience.


## 🚀 Features

* ####  🔐 User Authentication 
    * Secure signup & login 
    * Send welcome mail after signup
    * JWT-based authentication with cookies

* ####  💬 Real-Time Messaging
    * Instant message delivery
    * Online/offline status handling

* #### 🖼️ Image & Media Sharing
    * Send images in chat
    * Smooth preview & rendering

* #### 📇 Contacts & Chat List
    * View all available contacts
    * Recent chats & active conversations

* #### 🧑‍💻 User Profile
    * Profile updates
    * Avatar / profile picture support

* #### ⚡ Fast & Responsive UI
    * Tailwind CSS for modern styling
    * Optimized for performance


## 🛠️ Tech Stack
#### Frontend
    ⚛️ React + Vite
    🎨 Tailwind CSS
    🗂️ Zustand (State Management)
    🌐 Axios

#### Backend
    🟢 Node.js
    🚂 Express.js
    🗄️ MongoDB (Mongoose)
    🔐 JWT Authentication
    🍪 Cookie-based auth
    🔒 Arcjet (Security & rate limiting)


## 📸 Screenshots

#### 🔹 Signup Page
![Signup](frontend/public/screenshots/signup.png)

#### 🔹 Welcome Mail
![Welcome](frontend/public/screenshots/welcome.png)

#### 🔹 Login Page
![Login](frontend/public/screenshots/login.png)

#### 🔹 Contact List
![Contact](frontend/public/screenshots/contact.png)

#### 🔹 Chat Interface
![Chat](frontend/public/screenshots/chat.png)

#### 🔹 Real-Time Messaging
![Messaging](frontend/public/screenshots/messaging.png)

#### 🔹 Image / Media Sharing
![Sharing](frontend/public/screenshots/sharing.png)

#### 🔹 Porfile Pic Update
![Update](frontend/public/screenshots/update.png)


## ⚙️ Installation & Setup
#### 1️⃣ Clone the Repository
    git clone https://github.com/your-username/realtime-chat-app.git
    cd realtime-chat-app

#### 2️⃣ Backend Setup
    cd backend
    npm install

    Create a .env file:
        PORT=3000
        MONGO_URI=your_mongodb_uri
        JWT_SECRET=your_jwt_secret
        NODE_ENV=development
        CLIENT_URL=http://localhost:5173

    Start the backend:
        node src/server.js

##### Backend runs on:
    http://localhost:3000

#### 3️⃣ Frontend Setup
    cd frontend
    npm install
    npm run dev


##### Frontend runs on:
    http://localhost:5173

## 📂 Project Structure
    realtime-chat-app/
    │
    ├── backend/
    │   ├── node_modules/
    │   ├── src/
    │   │   ├── controllers/
    │   │   ├── emails/
    │   │   ├── lib/
    │   │   ├── middleware/
    │   │   ├── models/
    │   │   ├── routes/
    │   │   └── server.js
    │   │
    │   ├── .env
    │   └── package.json
    │
    ├── frontend/
    │   ├── dist/
    │   ├── node_modules/
    │   ├── public/
    │   ├── src/
    │   │   ├── components/
    │   │   ├── hooks/
    │   │   ├── lib/
    │   │   ├── pages/
    │   │   ├── store/
    │   │   ├── App.jsx
    │   │   ├── index.css
    │   │   └── main.jsx
    │   │
    │   ├── index.html
    │   ├── eslint.config.js
    │   ├── postcss.config.js
    │   ├── tailwind.config.js
    │   ├── vite.config.js
    │   ├── package.json
    │   ├── package-lock.json
    │   └── README.md
    │
    ├── .gitignore
    └── package.json
    └── README.md


## 🔐 Security Highlights

* Password hashing using bcrypt
* Protected routes with JWT
* Cookie-based authentication
* API protection using Arcjet


## 🧠 Future Improvements
✅ Typing indicators<br>
✅ Message read receipts<br>
✅ Group chats<br>
✅ Voice & video calling<br>
✅ Message search

## 🤝 Contributing
Contributions are welcome!<br>
Feel free to fork the repository and submit a pull request.


## 👨‍💻 Author
**Shashank Pandey<br>**
[![Email](https://img.shields.io/badge/Email-D14836?style=flat&logo=gmail&logoColor=white)](mailto:spandey21217@gmail.com)
[![LinkedIn](https://img.shields.io/badge/LinkedIn-0A66C2?style=flat&logo=linkedin&logoColor=white)](https://www.linkedin.com/in/shashank-pandey-292b3a251/)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat&logo=github&logoColor=white)](https://github.com/Shashank01234)