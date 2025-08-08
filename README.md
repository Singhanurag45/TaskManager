TaskManager - Task Management App
A modern Task Management Application built with React, Node.js, Express, and MongoDB to help you create, track, and manage tasks efficiently.
Includes features like status tracking, color-coded tasks, and real-time updates.

🚀 Features
📋 Add, View, Edit,  and Delete tasks

🎨 Color-coded tasks for quick status identification

📊 Task Statistics (Total, Completed, In Progress, Pending)

📅 Start Date and End Date tracking

🖥 Responsive UI for desktop

⚡ Real-time updates using API calls

🛠 Tech Stack
Frontend:

React.js

Axios

CSS3 (Custom Styling)

Backend:

Node.js

Express.js

MongoDB with Mongoose

📂 Project Structure
TaskManager/
│
├── backend/
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   ├── src/
│   ├── .env
│   ├── package-lock.json
│   ├── package.json
│
├── frontend/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   ├── styles/
│   │   ├── App.css
│   │   ├── App.jsx
│   │   ├── axios.js
│   │   ├── index.css
│   │   ├── main.jsx
│   ├── .gitignore
│   ├── eslint.config.js
│   ├── index.html
│   ├── package-lock.json
│   ├── package.json
│   ├── README.md
│   ├── vite.config.js
│
└── README.md


📸 Screenshots
![Task Manager Screenshot](https://github.com/Singhanurag45/TaskManager/blob/main/Screenshot%20(470).png?raw=true)
![Task Manager Screenshot](https://github.com/Singhanurag45/TaskManager/blob/main/Screenshot%20(471).png?raw=true)


⚙️ Installation & Setup
1️⃣ Clone the repository
bash
git clone https://github.com/Singhanurag45/TaskManager.git
cd TaskManager
2️⃣ Install dependencies
Backend

bash
cd backend
npm install
Frontend

bash
cd frontend
npm install
3️⃣ Configure Environment Variables
Create a .env file inside the backend folder and add:

ini
MONGO_URI=mongodb://localhost:27017/TaskManager
PORT=5000
4️⃣ Run the application
Backend

bash
cd backend
npm run dev
Frontend

bash
cd frontend
npm start
👨‍💻 Author
Anurag Singh
📧 Email: anuragsinghrbl2002@gmail.com
🔗 GitHub: Singhanurag45
