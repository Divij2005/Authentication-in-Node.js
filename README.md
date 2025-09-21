# 🔐 Node.js Authentication Assignment  

🛡️ A practical **authentication system** built with **Node.js and Express**, showcasing the use of **bcrypt** for password hashing and **JWT** for secure access to protected routes. 👨‍💻  

---

## 📝 Problem Statement  
Modern applications must ensure that user credentials are stored and validated securely. Plain text passwords are unsafe, and access control is essential for protecting user data. This assignment demonstrates:  
- **Task 1:** Secure password storage using **bcrypt**  
- **Task 2:** Authentication and authorization using **JWT tokens**  

---

## 📊 Current Progress Status  
- ✅ Task 1: Implemented password hashing with bcrypt  
- ✅ Task 2: Added JWT-based authentication and protected route  
- ✅ Register & Login APIs tested successfully  
- ✅ Protected `/profile` route working with valid tokens  

---

## 💡 Solution Overview  
The project ensures:  
- 🔐 Passwords are hashed before being stored (no plain text)  
- 🔑 Login validates hashed passwords securely  
- 🪙 JWT tokens are issued on successful login  
- 🚀 Protected endpoints can only be accessed with a valid token  

---

## 🛠️ Tech Stack  
- 🌐 **Node.js + Express** → Backend server  
- 🔒 **bcrypt** → Hashing and verifying passwords  
- 🪙 **jsonwebtoken (JWT)** → Token-based authentication  
- 📦 **body-parser** → Parse incoming JSON requests  

---

## 📸 API Routes  

### Task 1 – Password Hashing Authentication  
- `POST /register` → Create a user (hash password before storing)  
- `POST /login` → Verify user login with hashed password  

### Task 2 – JWT Authentication (with Hashing)  
- `POST /register` → Create a new user with hashed password  
- `POST /login` → Authenticate and generate JWT  
- `GET /profile` → Access protected data with JWT in `Authorization` header  

---

## ⚙️ How to Run  

1. 📥 **Clone repository**  
   ```bash
   git clone https://github.com/divij2005/auth-assignment.git
   cd auth-assignment
