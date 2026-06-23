# 🍳 Recipio — Recipe Finder App

A cross-platform recipe discovery application built with React Native, Expo, Express.js, and PostgreSQL. Recipio helps users discover new recipes, explore detailed cooking instructions, watch video tutorials, and save favorite recipes for quick access.

---

## 🚀 Features

### 🔐 Authentication

* Secure Signup and Login with Clerk
* 6-Digit Email Verification
* Session Management
* Protected User Data

### 🍽️ Recipe Discovery

* Browse Featured Recipes
* Explore Recipes by Categories
* Search Recipes Instantly
* View Detailed Recipe Information

### 🎥 Video Tutorials

* Integrated YouTube cooking tutorials
* Step-by-step visual cooking guidance

### ❤️ Favorites Management

* Save recipes to favorites
* Access favorite recipes anytime
* Synchronize user-specific favorites

### 🎨 Modern UI

* Clean and responsive mobile interface
* 8 Built-in Color Themes
* Optimized for Android and iOS

---

## 🛠️ Tech Stack

### Mobile App

* React Native
* Expo

### Backend

* Node.js
* Express.js

### Database

* PostgreSQL
* Neon Database

### Authentication

* Clerk

---

## 📁 Project Structure

```bash
RECIPIO/
│
├── backend/
│   ├── controllers/
│   ├── routes/
│   ├── models/
│   ├── middleware/
│   ├── server.js
│   └── package.json
│
├── mobile/
│   ├── app/
│   ├── assets/
│   ├── components/
│   ├── hooks/
│   ├── constants/
│   └── package.json
│
└── README.md
```

---

## 🔑 Environment Variables

### Backend (/backend)

Create a `.env` file inside the backend directory:

```env
PORT=5001
DATABASE_URL=your_neon_db_url
NODE_ENV=development
```

### Mobile App (/mobile)

Create a `.env` file inside the mobile directory:

```env
EXPO_PUBLIC_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
```

---

## ⚙️ Installation

### Clone the Repository

```bash
git clone https://github.com/your-username/recipio.git
cd recipio
```

### Install Backend Dependencies

```bash
cd backend
npm install
```

### Install Mobile Dependencies

```bash
cd mobile
npm install
```

---

## 🔧 Run the Backend

```bash
cd backend
npm run dev
```

Backend runs on:

```bash
http://localhost:5001
```

---

## 📱 Run the Mobile App

```bash
cd mobile
npx expo start
```

Scan the QR code using:

* Expo Go (Android)
* Camera App (iPhone)

---


## 🎯 Future Enhancements

* AI Recipe Recommendations
* Meal Planning
* Grocery List Generation
* Nutrition Tracking
* User Recipe Uploads
* Offline Recipe Access

---

## 🤝 Contributing

Contributions are welcome.

1. Fork the repository
2. Create a feature branch

```bash
git checkout -b feature-name
```

3. Commit changes

```bash
git commit -m "Add feature"
```

4. Push changes

```bash
git push origin feature-name
```

5. Open a Pull Request

---

## 👨‍💻 Author

**Vedant Kherade**

Built with ❤️ using React Native, Expo, Express.js, PostgreSQL, and Clerk.
