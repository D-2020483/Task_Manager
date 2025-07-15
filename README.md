# 🚀 Task_Manager Mini FullStack Project

This is a full-stack Task Manager Web Application design to help users efficiently manage their daily tasks and this is like a productivity tool that allows user to manage their personal or professional task with ease. It allows users to login to the application and using Task Dashboard users can create, delete, update and filter tasks with a responsive user interface.

---
### 🖥 Frontend Stack

- ⚛  *React.js*
- ⚡ *Vite* – Build tool
- 🎨 *Tailwind CSS*
- 🧩 *Material UI*
- 🧰 *Redux Toolkit* - State Management
- 🔗 *Axios* – For API communication
- 📝 *VS Code* – IDE

---
### 🔧 Backend Stack

- 🌐 *Node.js*
- 🚀 *Express.js*
- 🍃 *MongoDB Atlas*
- 🧬 *Mongoose*
- 🔐 *Authentication* - JWT (JSON Web Tokens)
- 📝 *VS Code* – IDE
- 🔥  *Thunder Client* - api testing

---
### 🚀 Features

- 🔐 User Authentication – Secure login and registration with token-based auth
- 🎯 Filter by Status – Quickly view tasks by status like "Pending", "Completed"
- 📅 Sort by Due Dates – Prioritize your workflow based on date eliyears to latest
- 🖥️ Responsive Dashboard – Built using MUI components with Tailwind styling
- 🌐 API Integration – Frontend communicates with a RESTful backend API using Axios
- ☁️ MongoDB Atlas – Cloud database for scalability and availability
---

### 🏗️ Architecture and the ER Diagram of the Application
<div align="center">
<img src="https://github.com/user-attachments/assets/ccbe7ed9-43c0-46f7-9341-8515c8a5e774"  alt="Task Manager Architecture" width="48%" style="margin-right: 15px;"/>
<img src="https://github.com/user-attachments/assets/918b92ba-a5cf-4452-bf72-72a451478f31" alt="ER Diagram" width="48%"/>
</div>

---
### 📸 Interface Screenshots

<img width="450" height="280" alt="Login Form" src="https://github.com/user-attachments/assets/3834795b-57d3-4aa6-8144-8b0135113f1a" /><br/>

<img width="450" height="280" alt="task_manager02" src="https://github.com/user-attachments/assets/ebd167eb-1e21-4cf7-af16-fcf60853058a" /><br/>

<img width="450" height="280" alt="task_manager03" src="https://github.com/user-attachments/assets/1094fe5f-62e3-40c0-9758-b204430547af" /><br/>

<img width="450" height="280" alt="task_manager04" src="https://github.com/user-attachments/assets/38c581df-f37e-4e2e-b4e6-cfe5e62a13ff" /><br/>

<img width="450" height="280" alt="task_manager05" src="https://github.com/user-attachments/assets/c7e7bd73-dc1c-4918-b64e-e58f852cfc30" /><br/>

<img width="450" height="280" alt="task_manager06" src="https://github.com/user-attachments/assets/28b69664-5379-42ad-85ae-1be1000e433a" /><br/>

<img width="450" height="280" alt="task_manager07" src="https://github.com/user-attachments/assets/9e701bf8-e5a6-411a-9f14-a189ab52cce6" /><br/>

---
### 🎨 Design Files and Wireframes
![Task Manager Wireframe](https://github.com/user-attachments/assets/12a07992-4633-4159-b03b-c6ea4f0596ff)
[🖼️ View full design on Figma](https://www.figma.com/design/F9qN0QT41vJhzcp4Zxoo70/Task_Manager?m=dev&t=vYGF59pfYDqMsGgh-1)

---
### 🔗 Repositories
- Frontend Repo:[Task Manager Frontend](https://github.com/D-2020483/Task_Manager_Frontend)
- Backend Repo:[Task Manager Backend](https://github.com/D-2020483/Task_Manager_Backend)
- Deployment Link:[Task Manager Deployment Link](https://task-manager-dinithi.netlify.app)
- Check the section below to see how to use the deployment link and how its work 
---
### 🔄 How It Works
1. User Registration and Authentication - New User can Register to the web application.Returning users login in securely via JWT-based authentication.

2. Task Management - After loggin in, users can create new tasks, update existing ones, or delete tasks they no longer need.

3. Filtering and Sorting - User can filter by status (ex: Pending, Completed) and sort them by due dates to organize their workflow efficiently.

4. Data Storage and Retrival - All task data is stored in a MongoDB Atlas cloud database. The backend API handles data requests and updates, ensuring persistent storage.

5. Frontend and Backend Communication - The React frontend communicates with the Node.js/Express backend through RESTful API endpoint using Axios, providing a smooth, real-time user experience.

---

### 🗺️ Step By Step Guide
👉 Step 1: Register and Login
- if you are using the Register Form just fill the all the filds and click the Register button.(Make sure to remember the password and email that you use to register)
- if you don't want to register, you can use the dummy credentials I provided to log in.
- (email : 111@gmail.com , password :1122)

👉 Step 2: Accessing the Dashboard
- if you use dummy data that (the provided email and the password) you will be taken directly to the dashboard page after loggin in.
- if you register a new account, after completing the registration you will be redirected to the Login page.
- just enter your registered email and password to log in and access the dashboard.

👉 Step 3: Create a Task
- Click the ADD TASK button, fill in task details,discription,due date and status, then save.

👉 Step 4: Filter and Sort Tasks
- Use the filter options to view tasks by status(Pending, Completed) .
- Use sorting options to arrange tasks by due date.
---

### 🛠️ Setup Instructions

Make sure you have the following installed:

- **Node.js**:`v24.3.0`
- **npm (Node Package Manager)**: `v10.5.1`

### 🖥️ Frontend Setup

👉 Clone the Repository

- Create a folder anywhere on your machine.
- open a terminal inside that folder.
- Run the following command to clone the frontend repository
- git clone https://github.com/D-2020483/Task_Manager_Frontend
- cd Task_Manager_Frontend

👉 Install Dependencies

- Copy the bellow commands and paste it in your terminal to install the dependencies
- npm install
- npm install react react-dom react-router-dom @reduxjs/toolkit react-redux axios @mui/material @emotion/react @emotion/styled lucide-react
- npm install -D vite tailwindcss postcss autoprefixer @tailwindcss/vite @vitejs/plugin-react-swc eslint @eslint/js eslint-plugin-react-hooks eslint-plugin-react-refresh globals @types/react @types/react-dom

👉 Run the Frontend
- npm run dev

### 🖥️ Backend Setup

👉 Clone the Repository

- Just hit cd .. in the terminal to get back to the root project folder
- Run the following command to clone the backend repository
- git clone https://github.com/D-2020483/Task_Manager_Backend
- cd Task_Manager_Backend in the terminal

👉 Install Dependencies

- Copy the bellow commands and paste it in your terminal to install the dependencies
- npm install
- .env file is already in the code base
- npm init -y
- npm install express mongoose cors dotenv bcryptjs jsonwebtoken
- npm install --save-dev nodemon

👉 Run the Backend

- npm run dev






