# 🚀 Postify

> A simple, interactive web application for managing posts — built to learn and practice core web development concepts.

[![Live Demo](https://img.shields.io/badge/Live%20Demo-Visit%20Now-brightgreen?style=for-the-badge)](https://postify-9q78.onrender.com/posts)
[![Node.js](https://img.shields.io/badge/Node.js-Express-339933?style=for-the-badge&logo=node.js)](https://nodejs.org/)
[![Deployed on Render](https://img.shields.io/badge/Deployed%20on-Render-46E3B7?style=for-the-badge)](https://render.com/)

---

## 🌐 Live Demo

👉 **[https://postify-9q78.onrender.com/posts](https://postify-9q78.onrender.com/posts)**

---

## ✨ Features

- 📄 View all posts in one place
- ➕ Create new posts with ease
- ✏️ Edit existing posts
- 🗑️ Delete posts you no longer need
- ⚡ Clean and minimal UI
- 🌍 Deployed and accessible online

---

## 🛠️ Tech Stack

| Layer | Technology |
|---|---|
| Frontend | HTML, CSS, EJS |
| Backend | Node.js, Express.js |
| Data Storage | In-memory / JSON |
| Deployment | Render |
| Version Control | Git & GitHub |

---

## 📁 Project Structure

```
postify/
│
├── public/          # Static files (CSS, images)
├── views/           # EJS templates
├── routes/          # Application routes
├── index.js         # Main server entry point
├── package.json     # Dependencies and scripts
└── README.md        # Project documentation
```

---

## 🚀 Getting Started

Follow these steps to run the project locally:

**1. Clone the repository**
```bash
git clone https://github.com/Kaushik1014/postify.git
```

**2. Move into the project folder**
```bash
cd postify
```

**3. Install dependencies**
```bash
npm install
```

**4. Start the server**
```bash
nodemon index.js
```

**5. Open in your browser**
```
http://localhost:3000/posts
```

---

## 🔗 API Endpoints

| Method | Endpoint | Description |
|---|---|---|
| `GET` | `/posts` | Retrieve all posts |
| `POST` | `/posts` | Create a new post |
| `GET` | `/posts/:id` | Get a single post by ID |
| `PUT` | `/posts/:id` | Update an existing post |
| `DELETE` | `/posts/:id` | Delete a post |

---

## 📌 Usage

1. Open the application in your browser
2. Click **New Post** to add content
3. Click **Edit** on any post to update it
4. Click **Delete** to remove a post

---

## 🤝 Contributing

Contributions, issues, and suggestions are always welcome!

To contribute:

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/your-feature`)
3. Commit your changes (`git commit -m 'Add your feature'`)
4. Push to the branch (`git push origin feature/your-feature`)
5. Open a Pull Request

Your support makes this project better. 🚀

---

## 👨‍💻 Author

**Kaushik Gautam**

Built with ❤️ for learning and practice.