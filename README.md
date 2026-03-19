# 🔗 BitLinks – Modern URL Shortener

BitLinks is a fast and minimal URL shortening application built with modern web technologies. It allows users to convert long URLs into short, shareable links with optional customization and instant redirection.

---

## ✨ Features

* 🔗 Convert long URLs into short links
* ✍️ Custom short URL support
* ⚡ Instant redirection
* 📱 Fully responsive UI
* 🧠 Efficient backend routing
* 💾 Persistent storage using MongoDB

---

## 🛠️ Tech Stack

### 💻 Frontend

* **Next.js 15 (App Router)**
* **React 19**
* **Tailwind CSS**
* **Custom Fonts (Geist, Poppins)**

### ⚙️ Backend

* **Next.js Route Handlers (API Routes)**
* **Node.js**

### 🗄️ Database

* **MongoDB**
* **MongoDB Native Driver**

### 🔧 Tools & Config

* **PostCSS**
* **ESLint**
* **Turbopack**
* **JSConfig (Path Aliasing)**

### 📡 Testing

* **Postman Collection**

---

## 📂 Project Structure

```bash
BitLinks/
│── app/              # App Router pages & API routes
│── components/       # Reusable UI components
│── dbconfig/         # MongoDB connection setup
│── models/           # Data schema definitions
│── public/           # Static assets
│── postman/          # API testing collection
│── package.json      # Dependencies & scripts
```

---

## ⚙️ Getting Started

### 1️⃣ Clone the repository

```bash
git clone https://github.com/sandhya0111/BitLinks.git
cd BitLinks
```

### 2️⃣ Install dependencies

```bash
npm install
```

### 3️⃣ Setup environment variables

Create a `.env.local` file:

```env
MONGODB_URI=your_mongodb_connection_string
NEXT_PUBLIC_HOST=http://localhost:3000
```

---

### 4️⃣ Run the app

```bash
npm run dev
```

Visit 👉 `http://localhost:3000`

---

## 🚀 How It Works

1. User submits a long URL
2. Server generates a unique short identifier
3. URL is stored in MongoDB
4. Visiting the short URL redirects to the original link

---

---

## 🤝 Contributing

Contributions are welcome!

1. Fork the repo
2. Create a new branch
3. Make your changes
4. Submit a pull request

---

## 📜 License

This project is licensed under the **MIT License**.

---

## 👩‍💻 Author

**Sandhya**
🔗 GitHub: [https://github.com/sandhya0111](https://github.com/sandhya0111)

---

## ⭐ Support

If you like this project, consider giving it a ⭐ on GitHub!

