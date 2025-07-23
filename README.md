# 🌟 Moments — A Full-Stack Social Media Platform

**Moments** is a modern full-stack social media application built with the **MERN stack**, featuring user posts, likes, comments, privacy control, follow system, and a clean responsive UI. It's built with modular architecture and real-world features to mimic modern social apps.

---

## 🚀 Features

- 📝 Create and share text/image posts
- 👍 Like and 💬 comment on posts
- 🔒 Public/private post visibility
- 👥 Follow and unfollow users
- 🔔 Get notified on post interactions (web only)
- ☁️ Upload images securely with **Cloudinary**
- 💡 Clean, modern UI using **Tailwind CSS**

---

## 🧰 Tech Stack

| Layer       | Tech               |
|-------------|--------------------|
| Frontend    | React.js, Tailwind CSS |
| Backend     | Node.js, Express.js |
| Database    | MongoDB, Mongoose |
| Media Upload | Cloudinary         |
| Auth        | JWT (JSON Web Tokens) |

---

## 📸 Screenshots

> *(Insert screenshots or a short screen recording GIF of the UI here)*

---

## 🛠️ Getting Started

### 📦 Clone the Repo

```bash
git clone https://github.com/jash15081/Moments.git
cd Moments
```
### Create a .env file inside the /server directory with the following keys:
```
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret_key
CLOUDINARY_CLOUD_NAME=your_cloudinary_cloud_name
CLOUDINARY_API_KEY=your_cloudinary_api_key
CLOUDINARY_API_SECRET=your_cloudinary_api_secret
```

### Install dependencies and run the app with one command:
```
npm install
npm run dev
```

## File structure
```
Moments/
├── client/         # React frontend
│   ├── components/
│   ├── pages/
│   └── utils/
├── server/         # Express backend
│   ├── controllers/
│   ├── models/
│   ├── routes/
│   └── utils/
└── README.md
```

## 🧠 What I Learned

- 🏗️ Designing scalable full-stack architecture
- ☁️ Handling image uploads with **Cloudinary**
- 🔒 Implementing secure authentication and route protection
- ⚛️ Managing UI state and dynamic rendering in React
- 🧩 Writing modular, reusable components and clean APIs

---

## 🚧 Future Improvements

- 🔔 Real-time notifications with **Socket.IO**
- 💬 Chat or direct messaging feature
- 📷 Story-sharing similar to Instagram
- 🔄 Infinite scroll or pagination in feeds
- 📲 Push notifications for web and mobile
