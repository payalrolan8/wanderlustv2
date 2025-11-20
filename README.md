# 🌍 Wanderlust

A full-stack travel-listing web application inspired by Airbnb. Users can create listings, browse locations, leave reviews, and manage their personal listings.

---

## ✨ Features

### 🔐 **User Authentication**

* Login / Register
* Session-based authentication
* Protected routes
* Flash messages

### 🏠 **Listings**

* Create, edit, and delete listings
* Upload images
* Store listing data in MongoDB
* Public listings available without login

### ⭐ **Reviews**

* Add and delete reviews
* Rating system
* Server-side validation

### ⚙️ **Other Features**

* Custom middleware
* Cloud image upload (Cloudinary config)
* Clean folder structure (controllers, routes, models, utils, etc.)

---

## 🛠️ Tech Stack

**Backend**

* Node.js
* Express.js

**Database**

* MongoDB (Mongoose)

**Frontend**

* EJS Templates
* Public assets (CSS / JS)

**Other Tools**

* Cloudinary / multer
* Passport.js authentication
* Express-session
* Joi validation

---

## 📂 Project Structure

```
project/
│── controller/       # All route logic (listings, reviews, users)
│── routes/           # Express route files
│── models/           # Mongoose schemas
│── public/           # Static assets (CSS, JS, images)
│── utils/            # Utility functions and helper files
│── middleware.js     # Custom middleware
│── cloudconfig.js    # Cloudinary configuration
│── app.js            # Main server file
│── init/             # Seed or initial setup scripts
│── storage/          # Optional uploaded/local files
│── package.json
│── package-lock.json
```

---

## ⚙️ Installation & Setup

### **1️⃣ Clone the repository**

```bash
git clone https://github.com/your-username/wanderlust.git
cd wanderlust
```

### **2️⃣ Install dependencies**

```bash
npm install
```

### **3️⃣ Create a `.env` file**

(Do NOT commit this file)

Example:

```
CLOUDINARY_CLOUD_NAME=xxxx
CLOUDINARY_API_KEY=xxxx
CLOUDINARY_API_SECRET=xxxx
SESSION_SECRET=your_secret
MONGO_URL=your_mongodb_url
```

### **4️⃣ Start the app**

```bash
npm start
```

Now visit:
👉 **[http://localhost:8080](http://localhost:8080)**

---

## 📝 Scripts

```bash
npm start        # Start the server
npm run dev      # Start with nodemon (if configured)
```
