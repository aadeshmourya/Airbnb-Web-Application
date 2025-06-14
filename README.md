# Airbnb Web Application

A full-stack Airbnb clone built with Node.js, Express, MongoDB, and Tailwind CSS. This application allows users to register, log in, create property listings, upload images, and browse stays. It mimics key features of the real Airbnb platform with a clean, responsive interface.

## 🚀 Features

- User registration and login with hashed passwords
- Host property listings with image uploads
- Browse available stays with details
- EJS-based templating for server-side rendering
- MongoDB integration using Mongoose
- Tailwind CSS for responsive design
- Session and cookie management
- MVC-based project architecture

## 🛠️ Tech Stack

- **Frontend**: EJS, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB (via Mongoose)
- **Authentication**: bcryptjs, express-session
- **File Uploads**: multer

## 📁 Folder Structure

Airbnb Web Application/
├── app.js
├── controllers/
├── models/
├── routes/
├── views/
├── public/
├── utils/
├── package.json
├── tailwind.config.js


## ⚙️ Installation

1. Clone the repository:

   bash
   git clone https://github.com/your-username/airbnb-web-app.git
   cd airbnb-web-app


2. Install dependencies:

   bash
   npm install
  

3. Start the development server:

   bash
   npm start
  

## 📝 Scripts

* npm start: Runs the app with `nodemon` and watches Tailwind CSS
* npm run tailwind: Runs only the Tailwind CSS build watcher
