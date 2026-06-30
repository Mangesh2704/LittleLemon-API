# Little Lemon API (Backend Capstone Project)

## 👩‍💻 Developer  
Mangesh Pangam  

---

## 📌 Project Overview  
This project is a backend application built using **Django REST Framework** for the Little Lemon restaurant. It provides APIs to manage menu items, reservations, and orders along with secure user authentication.

---

## 🚀 Key Features  
- RESTful API implementation using Django REST Framework  
- MySQL database integration  
- CRUD operations for menu items  
- Reservation (booking) management  
- Orders handling system  
- User authentication with Djoser and Token Auth  
- Protected API endpoints  
- Unit testing included  
- Compatible with Insomnia / Postman  

---

## ⚙️ Installation & Setup  

### 1. Clone the repository  
```bash
git clone https://github.com/Mangesh2704/LittleLemon-API.git
cd littlelemon-api
```

### 2. Install dependencies  
```bash
pip install -r requirements.txt
```

### 3. Configure MySQL  
Update your database credentials in the `settings.py` file.

### 4. Apply migrations  
```bash
python manage.py migrate
```

### 5. Run the server  
```bash
python manage.py runserver
```

---

## 🔗 API Endpoints  

### 📍 Menu API  
```
GET     /restaurant/menu/
POST    /restaurant/menu/
GET     /restaurant/menu/<id>/
PUT     /restaurant/menu/<id>/
DELETE  /restaurant/menu/<id>/
```

### 📍 Reservation API  
```
GET     /restaurant/reservations/
POST    /restaurant/reservations/
```

### 📍 Orders API  
```
GET     /restaurant/orders/
POST    /restaurant/orders/
```

### 🔐 Authentication APIs  
```
POST    /auth/users/                Register user
POST    /auth/token/login/          Login user
POST    /auth/token/logout/         Logout user
POST    /restaurant/api-token-auth/ Generate authentication token
```

### 🔒 Protected Endpoint Example  
```
GET     /restaurant/message/
```
(Requires authentication token)

---

## 🧪 Running Unit Tests  
```bash
python manage.py test
```

---

## 🛠️ Tech Stack  
- Python  
- Django  
- Django REST Framework  
- MySQL  
- Djoser  

---

## 📌 Notes  
- Use Insomnia or Postman to test the APIs  
- Ensure MySQL service is running before starting the server  

---

## 🌐 Repository  
👉 https://github.com/Mangesh2704/LittleLemon-API.git
