
# Mini Social App 🧑‍💬

A simple Node.js-based social app that supports user registration, login, creating posts, liking posts, editing, and deleting them. Additionally, users can upload a profile picture. Built with modern web technologies and a clean, user-friendly interface.

## 🛠️ Features

* **User Authentication** using JWT and cookies
* **Password Hashing** with bcrypt
* **CRUD Operations** for posts (Create, Read, Update, Delete)
* **Like/Unlike Posts** functionality
* **Image Upload** for profile pictures using Multer
* **EJS** for rendering dynamic views
* **MongoDB** with **Mongoose** for data storage
* **Responsive UI** with **Tailwind CSS**

---

## 🚀 Tech Stack

* **Backend**: Node.js, Express.js
* **Frontend**: EJS, Tailwind CSS (via CDN)
* **Database**: MongoDB (Mongoose ODM)
* **Auth**: JWT (JSON Web Tokens), bcrypt (Password Hashing)
* **File Upload**: Multer (for profile pictures)
* **Styling**: Tailwind CSS

---

## ⚙️ Getting Started

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/mini-social-app.git
cd mini-social-app
```

### 2. Install Dependencies

```bash
npm install
```

### 3. Set Up MongoDB

Make sure MongoDB is installed and running on your machine or use a cloud MongoDB service.

For a local MongoDB setup, use the default URI:

```
mongodb://localhost:27017/socialapp
```

Alternatively, if you are using MongoDB Atlas or another cloud service, update the connection string in the application accordingly.

### 4. Create Uploads Folder

Make sure there is an `uploads` folder inside the `/public` directory to store uploaded profile pictures:

```
/public/uploads
```

### 5. Run the App

To start the application:

```bash
node app.js
```

Visit `http://localhost:3000` in your browser.
