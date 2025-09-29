# COOKIE & SESSION AUTHENTICATION

## Bài lab thực hành xác thực bằng **Cookie + Session** trong NodeJS.

---

## ⚙️ Run project
```bash
npm install
node app.js
```

---

## 🧪 Test with Postman

### 🔹 Register
**POST** `http://localhost:3000/auth/register`  
Body → raw (JSON):
```json
{ "username": "admin", "password": "123456" }
```
📸 ![Register](img/register.png)

---

### 🔹 Login
**POST** `http://localhost:3000/login`  
📸 ![Login](public/results/login.png)

---

### 🔹 Profile
**GET** `http://localhost:3000/profile`  
📸 ![Profile](public/results/profile.png)

---

### 🔹 Logout
**GET** `http://localhost:3000/logout`  
📸 ![Logout](public/results/logout.png)

---

## 📘 Author
**22670361 - Võ Thị Cẩm Tú**
