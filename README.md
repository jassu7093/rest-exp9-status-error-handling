# 🧪 REST API Experiment 9 — Status Codes and Error Handling for Invalid Requests

## 📘 Objective
To implement proper **HTTP status codes** and structured **error handling** for invalid or failed API requests in an Express + Mongoose REST API.

---

## 🧠 Learning Outcomes
- Understand and apply **HTTP response codes** (200, 201, 400, 404, 500, etc.).  
- Handle **invalid requests** gracefully with meaningful error messages.  
- Centralize error-handling logic using **Express middleware**.  
- Improve API reliability and maintainability.

---

## ⚙️ Tools & Technologies
- **Node.js**
- **Express.js**
- **MongoDB / Mongoose**
- **dotenv**
- **Postman**
- **VS Code**

---

## 🏗️ Folder Structure
rest-exp9-status-error-handling/
│
├── server.js
├── models/
│ └── Student.js
├── routes/
│ └── studentRoutes.js
├── middleware/
│ └── errorHandler.js
├── .env
├── .env.example
├── package.json
└── README.md


---

## 🚀 Setup Instructions
```bash
# Step 1: Initialize Node project
npm init -y

# Step 2: Install dependencies
npm install express mongoose dotenv

# Step 3: Create folders
mkdir models routes middleware
touch server.js models/Student.js routes/studentRoutes.js middleware/errorHandler.js .env .env.example

# Step 4: Run the server
node server.js
```

## output
<img width="1080" height="701" alt="rest_9 (2)" src="https://github.com/user-attachments/assets/2ce9c38d-b71c-427c-82cd-b84cdf4e565b" />
<img width="1080" height="699" alt="rest_9 (1)" src="https://github.com/user-attachments/assets/f0eaca5f-f116-4981-a198-80858815fc63" />
<img width="1079" height="701" alt="rest_9 (3)" src="https://github.com/user-attachments/assets/20ae8661-30de-416e-8ddc-94e87d548766" />


