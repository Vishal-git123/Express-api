# 🚀 Express API

A simple REST API built using Node.js and Express.js that performs basic CRUD (Create, Read, Update, Delete) operations.

This project was created for learning backend fundamentals and understanding how APIs work in Express.js.

---

## 🌐 Live Deployment

**API is live on Render:** https://express-api-1-4wl2.onrender.com/

---

## 📌 Features

- Create data using POST request
- Read data using GET request
- Update existing data using PATCH request
- Delete data using DELETE request
- REST API architecture
- JSON data handling

---

## 🛠️ Tech Stack

- Node.js
- Express.js
- JavaScript
- Deployed on Render

---

## 📂 Project Structure

```bash
Express-api/
│
├── index.js
├── package.json
├── package-lock.json
├── MOCK_DATA.json
├── task.txt
└── README.md
```

---

## 🔗 API Endpoints

| Method | Endpoint | Description |
|--------|----------|-------------|
| GET | `/` | API status |
| GET | `/api/users` | Get all users (JSON) |
| GET | `/users` | Get all users (HTML) |
| GET | `/api/users/:id` | Get user by ID |
| POST | `/api/users` | Create new user |
| PUT | `/api/users/:id` | Update user |
| DELETE | `/api/users/:id` | Delete user |

---

## 📝 Example Requests

### Get All Users
```bash
curl https://express-api-1-4wl2.onrender.com/api/users
```

### Get Single User
```bash
curl https://express-api-1-4wl2.onrender.com/api/users/1
```

### Get Users (HTML View)
```bash
curl https://express-api-1-4wl2.onrender.com/users
```

---

## ⚙️ Installation & Setup (Local)

```bash
# Clone the repository
git clone https://github.com/Vishal-git123/Express-api.git

# Install dependencies
npm install

# Start the server
npm start
```

The server will run on `http://localhost:8000`

---

## 📄 License

ISC
