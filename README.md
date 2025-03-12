# Expense Management System (MERN Stack)

## 📌 Project Overview
The **Expense Management System** is a full-stack web application built using the **MERN stack** (MongoDB, Express.js, React.js, and Node.js). It allows users to manage expenses, track spending, and visualize financial data.

### 🌐 Live Demo
- **Frontend (React App)**: [Expense Management System Live](https://expense-management-system-using-mern-1.onrender.com)


## 🚀 Features
✅ User authentication (Login & Signup)  
✅ Add, update, and delete expenses  
✅ View expense history  
✅ Expense categorization  
✅ Data visualization for spending trends  
✅ Responsive UI/UX  
✅ Deployed on **Render**  

---

## 🏗 Tech Stack
### 💻 Frontend
- React.js (Vite)
- Tailwind CSS (for styling)
- Axios (for API requests)

### 🖥 Backend
- Node.js
- Express.js
- MongoDB (with Mongoose)
- JWT Authentication
- bcrypt.js (for password hashing)

### ☁ Deployment
- **Frontend:** Hosted on Render
- **Backend:** Hosted on Render
- **Database:** MongoDB Atlas

---

## 🛠 Setup & Installation

### 1️⃣ Clone the Repository
```sh
 git clone https://github.com/yaskivamshi/Expense-Management-System-using-mern.git
 cd Expense-Management-System-using-mern
```

### 2️⃣ Backend Setup (Server)
```sh
 cd server
 npm install
```

#### Create a `.env` file in the `server` directory and add:
```
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
```

#### Run the Backend Server
```sh
 npm start
```
The backend will run at `http://localhost:5000`

### 3️⃣ Frontend Setup (Client)
```sh
 cd ../client
 npm install
```

#### Create a `.env` file in the `client` directory and add:
```
VITE_BACKEND_URL=http://localhost:5000
```

#### Start the React Frontend
```sh
 npm run dev
```
The frontend will run at `http://localhost:5173`

---

## 🔗 API Endpoints
### 📝 Authentication
- `POST /api/auth/register` → Register a new user
- `POST /api/auth/login` → User login

### 💰 Expenses
- `GET /api/expenses` → Fetch all expenses
- `POST /api/expenses` → Add a new expense
- `PUT /api/expenses/:id` → Update an expense
- `DELETE /api/expenses/:id` → Delete an expense

---

## 🚀 Deployment on Render
### 1️⃣ Deploy Backend (Server)
- Push your code to GitHub.
- Create a **Web Service** on [Render](https://render.com/).
- Link it to your repository (`server` folder).
- Add environment variables (`MONGODB_URI`, `JWT_SECRET`).
- Deploy & get the live backend URL.

### 2️⃣ Deploy Frontend (Client)
- Build the project using:
  ```sh
  cd client
  npm run build
  ```
- Deploy the `dist` folder to Render as a static site.
- Update the `VITE_BACKEND_URL` in `.env` to your Render backend URL.
- Deploy & get the live frontend URL.

---

## 📸 Screenshots
_Add UI screenshots here_
![image](https://github.com/user-attachments/assets/df0e30d2-de05-494d-b5c0-42b02ad56343)
![image](https://github.com/user-attachments/assets/aa1fbc22-de2f-4696-9837-560dede9b54b)
![image](https://github.com/user-attachments/assets/b848d2fd-d56d-466c-b19b-9ade9faa4d9b)



---

## 🤝 Contributing
1. Fork the repository
2. Create a feature branch (`git checkout -b feature-branch`)
3. Commit changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a **Pull Request**

---

## 🛡 Security
- Uses **JWT Authentication** for secure login.
- Passwords are hashed using `bcrypt.js`.
- API endpoints are protected from unauthorized access.

---

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

---

## 📞 Contact
- GitHub: [yaskivamshi](https://github.com/yaskivamshi)
- LinkedIn: https://www.linkedin.com/in/vamshi-yaski/
- Email: vamshiyaski66@gmail.com

> ⭐ If you like this project, please give it a star on GitHub! ⭐

