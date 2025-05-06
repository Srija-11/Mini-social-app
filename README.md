# Mini Social App 🧑‍💬

A simple Node.js-based social app that supports user registration, login, creating posts, liking posts, and editing them.

## 🛠️ Features

- User authentication using JWT and cookies
- Password hashing with bcrypt
- Create, view, like/unlike, and edit posts
- EJS for rendering views
- MongoDB with Mongoose for data storage

## 🚀 Tech Stack

- **Backend**: Node.js, Express.js
- **Frontend**: EJS, Tailwind CSS (via CDN)
- **Database**: MongoDB (Mongoose ODM)
- **Auth**: JWT, bcrypt


Follow these steps to set up and run the project locally:

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/mini-social-app.git
cd mini-social-app
````

### 2. Install Dependencies

```bash
npm install
```

### 3. Set Up MongoDB

Ensure you have MongoDB installed and running on your machine. The app connects to a local MongoDB instance by default:

```bash
mongodb://localhost:27017/socialapp
```

You can change the connection string inside `models/user.js` and `models/post.js` if needed.

Alternatively, start MongoDB with Docker:

```bash
docker run -d -p 27017:27017 --name social-mongo mongo
```

### 4. Run the App

```bash
node app.js
```

Visit the app at: [http://localhost:3000](http://localhost:3000)

