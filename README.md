# 🏠 Room Renting Application

A web-based **Room Renting Application** built using **Node.js, Express.js, EJS, and MongoDB**. The application allows users to explore available rooms and view room details through a simple and user-friendly interface.

## 🚀 Live Demo

### AWS EC2 Deployment

🔗 http://107.22.64.46:3003/

### Render Deployment

🔗 https://room-55.onrender.com/

## 📌 Project Overview

The Room Renting Application is a web application designed to help users explore rooms available for rent.

The application provides a platform where users can browse room listings and view detailed information about available properties.

The backend is developed using **Node.js and Express.js**, **EJS** is used for server-side rendering, and **MongoDB** is used as the database.

## ✨ Features

* 🏠 View available rooms
* 🔍 Explore room details
* 📝 Display room information
* 🖼️ Display room/property images
* 📍 Property information
* 👤 User-friendly interface
* 🗄️ MongoDB database integration
* ⚡ Express.js backend
* 📄 EJS server-side rendering
* ☁️ AWS EC2 deployment
* 🌐 Render deployment

## 🛠️ Technologies Used

### Frontend

* HTML5
* CSS3
* JavaScript
* EJS
* Bootstrap

### Backend

* Node.js
* Express.js

### Database

* MongoDB

### Deployment & Tools

* AWS EC2
* Render
* Git
* GitHub
* VS Code
* Postman

## 📂 Project Structure

```text
Room-Renting-Application/
│
├── public/
│   ├── css/
│   ├── js/
│   └── images/
│
├── views/
│   ├── listings/
│   ├── layouts/
│   └── ...
│
├── routes/
│   └── ...
│
├── models/
│   └── ...
│
├── app.js
├── package.json
├── package-lock.json
└── README.md
```

> The exact folder structure may vary depending on the project implementation.

## 🗄️ Database

The application uses **MongoDB** to store room/property listing information.

MongoDB is used for managing application data such as:

* Room details
* Property information
* Images
* Location information
* Pricing
* Listing information

## ⚙️ Installation & Setup

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
```

### 2. Navigate to the project directory

```bash
cd Room-Renting-Application
```

### 3. Install dependencies

```bash
npm install
```

### 4. Configure MongoDB

Create a MongoDB database and configure the MongoDB connection in the application.

Example:

```javascript
mongoose.connect("YOUR_MONGODB_CONNECTION_STRING");
```

Replace the connection string with your own MongoDB connection string.

### 5. Start the application

```bash
node app.js
```

The application will run locally on:

```text
http://localhost:3003
```

## 🔐 Environment Variables

For security, sensitive information such as database credentials should be stored using environment variables.

Example `.env`:

```env
MONGODB_URI=your_mongodb_connection_string
PORT=3003
```

> Never upload your `.env` file or database credentials to GitHub.

## ☁️ AWS EC2 Deployment

The application is also deployed on an **AWS EC2 Ubuntu server**.

### AWS Deployment

```text
AWS EC2
   ↓
Ubuntu Server
   ↓
Node.js
   ↓
Express.js Application
   ↓
MongoDB
   ↓
Port 3003
```

### Live AWS URL

http://107.22.64.46:3003/

The application was configured to listen on the server's network interface so that it can be accessed externally through the EC2 public IP.

## 🌐 Render Deployment

The application is also deployed using **Render**.

### Live Render URL

https://room-55.onrender.com/

## 🔄 Application Flow

```text
User
  ↓
Browser
  ↓
Express.js Server
  ↓
Routes
  ↓
MongoDB
  ↓
Room Data
  ↓
EJS Views
  ↓
Browser
```

## 🎯 Learning Outcomes

By developing this project, I gained practical experience in:

* Node.js
* Express.js
* EJS
* MongoDB
* Backend development
* Database integration
* CRUD concepts
* Server-side rendering
* Routing
* REST API concepts
* Git and GitHub
* AWS EC2
* Linux server deployment
* Node.js application deployment
* Render deployment

## 🔮 Future Improvements

The following features can be added in future versions:

* 👤 User authentication
* 🔐 Login and registration
* 🏠 Owner dashboard
* 📋 Add and manage room listings
* 🔎 Advanced search and filtering
* 📍 Map integration
* 💬 User and owner messaging
* 📅 Room booking
* 💳 Online payment
* ⭐ Reviews and ratings
* 🔔 Notifications

## 👨‍💻 Author

**Karan Awari**

B.Sc. Computer Science Graduate | MERN Stack Developer

### Skills

* HTML5
* CSS3
* JavaScript
* React.js
* Node.js
* Express.js
* MongoDB
* MySQL
* Bootstrap
* Git
* GitHub
* AWS EC2

## ⭐ Support

If you find this project useful, consider giving it a ⭐ on GitHub.
