# 📝 Task Manager Application  

A full-stack **Task Manager Application** built using **Django REST framework for the backend** and **React.js for the frontend**. This application allows users to **create, update, and delete tasks**, with user authentication implemented via **dj-rest-auth**.

---

## 🚀 Technologies Used  

### 🖥️ **Frontend (React.js)**
- **React.js** (JavaScript Library)
- **Axios** (For API requests)
- **Bootstrap & Reactstrap** (For styling)
- **React Router** (For navigation)

### 🖥️ **Backend (Django & Django REST Framework)**
- **Django** (Web framework)
- **Django REST Framework** (For building REST APIs)
- **dj-rest-auth** (For authentication)
- **djoser** (For user registration & authentication)
- **PostgreSQL / SQLite** (Database)
- **Corsheaders** (For handling CORS issues)

---

## ⚙️ Setup Guide  

### 1️⃣ **Clone the Repository**
```sh
git clone https://github.com/your-username/your-repo-name.git
cd your-repo-name
```

---

## 🖥️ **Backend Setup (Django)**
### 2️⃣ **Create and Activate Virtual Environment**
```sh
python -m venv venv
source venv/bin/activate  # On Mac/Linux
venv\Scripts\activate      # On Windows
```

### 3️⃣ **Install Backend Dependencies**
```sh
pip install -r requirements.txt
```

### 4️⃣ **Apply Migrations & Create Superuser**
```sh
python manage.py migrate
python manage.py createsuperuser
```

### 5️⃣ **Run the Django Server**
```sh
python manage.py runserver
```
Your Django API will be live at **`http://127.0.0.1:8000/`** 🚀

---

## 🌐 **Frontend Setup (React)**
### 6️⃣ **Navigate to the Frontend Directory**
```sh
cd frontend
```

### 7️⃣ **Install Frontend Dependencies**
```sh
npm install
```

### 8️⃣ **Run the React Application**
```sh
npm start
```
Your React app will be live at **`http://localhost:3000/`** 🎉

---

## 🔑 **Authentication API Endpoints**  
- **Register:** `POST /auth/registration/`  
- **Login:** `POST /auth/login/`  
- **Logout:** `POST /auth/logout/`  
- **Get Tasks:** `GET /api/tasks/`  
- **Create Task:** `POST /api/tasks/`  
- **Update Task:** `PUT /api/tasks/:id/`  
- **Delete Task:** `DELETE /api/tasks/:id/`  

---

## 📌 **Features**
✅ **User Authentication** (Sign Up, Login, Logout)  
✅ **Create, Read, Update, Delete (CRUD) Tasks**  
✅ **Responsive UI with Bootstrap**  
✅ **Django REST Framework API**  
✅ **Secure Token-based Authentication**  

---

## 🎯 **Contributing**  
Feel free to fork this project, raise issues, and submit pull requests.  

---

## 📄 **License**  
This project is licensed under the MIT License.  

---

## 🎉 **Happy Coding!** 🚀  

---

This README is **GitHub-friendly**, well-structured, and provides a clear setup guide. Let me know if you need any modifications! 😊
