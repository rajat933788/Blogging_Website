# 💻 Blog Post App

A full-stack blog application built with **React**, **Node.js**, and **MySQL** that allows users to authenticate, create, edit, and manage blog posts.

---

## 📌 About the Project

This project demonstrates how to integrate **React**, **Node.js**, and **MySQL** to build a robust and scalable blogging platform.

### Highlights:

* Backend developed using **Node.js** and **Express** for API routing and server-side logic.
* Frontend designed with **React** for a dynamic and responsive user experience.
* **MySQL** is used as the database to manage users and blog content with full CRUD support.

You’ll learn how to:

* Connect a Node.js backend to a MySQL database.
* Perform Create, Read, Update, Delete (CRUD) operations.
* Handle user authentication and secure routes.
* Build reusable components and manage state in React.

---

## ✨ Features

* ✅ **User Authentication**: Sign up, log in, and log out.
* 🔐 **Authorization**: Only logged-in users can modify or delete their own posts.
* 📝 **Post Management**: Full CRUD operations for blog posts.
* 📄 **Pagination**: Efficient browsing through paginated post lists.
* 🔍 **Filtering**: View posts based on selected topics.

---

## ⚙️ Getting Started

To run this project locally, follow the steps below:

### 1. Clone the Repository

```bash
git clone https://github.com/rajat933788/Blogging_Website
cd Blogging_Website
```

### 2. Install Dependencies

Install the required packages for both the frontend (`front`) and backend (`api`):

```bash
# Frontend
cd frontend
npm install

# Backend
cd backend
npm install
```

### 3. Set Up the Database

* Create a new MySQL database.
* Import the SQL schema files provided in the project (`SQL_users`, `SQL_posts`).
* Update your DB connection details in the backend configuration file (e.g., `.env` or `db.js`).

### 4. Run the Application

Start the backend and frontend servers:

```bash
# Start backend
cd backend
npm run dev

# Start frontend
cd frontend
npm start
```

---

## 🛠 Tech Stack

**Frontend:**

* [ReactJS](https://reactjs.org/)
* [Axios](https://axios-http.com/)

**Backend:**

* [Node.js](https://nodejs.org/)
* [Express.js](https://expressjs.com/)

**Database:**

* [MySQL](https://www.mysql.com/)
* [MySQL Workbench](https://www.mysql.com/products/workbench/)

---

## 📖 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for more information.

---

## 👨‍💻 Author

**Rajat Bagh**
Full-Stack Developer
📍 India
