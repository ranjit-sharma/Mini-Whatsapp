# 💬 Mini WhatsApp

A **Mini WhatsApp chat application** built using **Node.js, Express.js, MongoDB, Mongoose, and EJS**.

This project demonstrates how to build a backend application with complete **CRUD operations** and dynamic pages using EJS.

> This is a learning project inspired by a chat application. It is not the official WhatsApp application.

## 🚀 Features

- 💬 View all chats
- ➕ Create a new chat
- ✏️ Edit a chat message
- 🗑️ Delete a chat
- 🗄️ Store chat data in MongoDB
- 🔄 Complete CRUD operations using Mongoose
- 🎨 Dynamic pages using EJS
- 📅 Store chat creation time
- 🌐 Express.js routing
- 🎨 Static CSS styling

## 🛠️ Technologies Used

- **Node.js** – Backend runtime
- **Express.js** – Web framework and routing
- **MongoDB** – Database
- **Mongoose** – MongoDB ODM
- **EJS** – Dynamic HTML templates
- **HTML5 & CSS3** – Frontend
- **Method Override** – PUT and DELETE requests from forms

## 📂 Project Structure

```text
Mini-Whatsapp/
│
├── models/
│   └── chat.js
├── public/
│   └── style.css
├── views/
│   ├── index.ejs
│   ├── new.ejs
│   └── edit.ejs
├── index.js
├── init.js
├── package.json
├── package-lock.json
├── .gitignore
└── README.md
```

## 🔄 CRUD Operations

| Operation | Method | Route | Purpose |
|---|---|---|---|
| Create | POST | `/chats` | Create a new chat |
| Read | GET | `/chats` | Display all chats |
| Update | PUT | `/chats/:id` | Edit a chat message |
| Delete | DELETE | `/chats/:id` | Delete a chat |

## ▶️ How to Run

### 1. Clone the repository

```bash
git clone https://github.com/ranjit-sharma/Mini-Whatsapp.git
```

### 2. Open the project

```bash
cd Mini-Whatsapp
```

### 3. Install dependencies

```bash
npm install
```

### 4. Start MongoDB

Make sure MongoDB is running on your computer.

The project connects to:

```text
mongodb://127.0.0.1:27017/whatsapp
```

### 5. Start the server

```bash
node index.js
```

### 6. Open in browser

```text
http://localhost:8080/chats
```

## 🗃️ Database

Database:

```text
whatsapp
```

The Chat model contains:

- `from` – sender
- `to` – receiver
- `msg` – message
- `created_at` – chat creation date and time

## 📚 What I Learned

While building this project, I practiced:

- Creating an Express.js server
- Creating GET, POST, PUT and DELETE routes
- Connecting Node.js with MongoDB
- Creating Mongoose schemas and models
- Using `find()`, `findById()`, and `save()`
- Using `findByIdAndUpdate()`
- Using `findByIdAndDelete()`
- Working with `req.params` and `req.body`
- Using `express.urlencoded()`
- Using `method-override`
- Rendering dynamic pages with EJS
- Serving static files with Express
- Organizing a backend project into models, views and public folders

## 🔮 Future Improvements

- 🔐 Add user authentication
- 👤 Add user profiles
- 🔍 Add chat search
- 📱 Improve responsive design
- ⚡ Add real-time messaging using Socket.IO
- 🎨 Improve the chat interface

## 👨‍💻 Author

**Ranjit Sharma**

GitHub: https://github.com/ranjit-sharma/Mini-Whatsapp

---

⭐ Built as a learning project to practice backend development with Node.js, Express.js and MongoDB.
