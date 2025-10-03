# 📱 Social Media Web Application (MERN Stack)

A fully functional **social media web application** built with the **MERN Stack (MongoDB, Express.js, React.js, Node.js)**, featuring real-world architecture and modern tooling. This project demonstrates full-stack development skills with authentication, chat, media uploads, and background job handling.  

---

## 🚀 Features

### 🔑 User Authentication
- Secure **sign-up, sign-in, and profile management** powered by **[Clerk](https://clerk.dev/)**.

### ⚡ Background Jobs
- Asynchronous & scheduled task handling with **[Inngest](https://www.inngest.com/)**.

### 🖼️ Media Storage & Optimization
- Image upload, optimization, and fast delivery with **[ImageKit](https://imagekit.io/)**.

### 🌐 Core Social Features
- Real-time **chat and messaging**  
- **Post and feed system** (text & image-based content)  
- **Follow / Unfollow** functionality  
- **Friend requests management**  
- **Stories / status uploads**  
- **User search & discovery**

---

## 🛠️ Tech Stack

- **Frontend:** React.js, Tailwind CSS  
- **Backend:** Node.js, Express.js  
- **Database:** MongoDB (Mongoose)  
- **Authentication:** Clerk  
- **Background Jobs:** Inngest  
- **Media Storage:** ImageKit  
- **Deployment:** Vercel / Netlify (frontend) & Render / Railway (backend)  

---

## 📂 Project Structure

```bash
├── client/              # React frontend
│   ├── src/
│   └── public/
├── server/              # Express backend
│   ├── models/          # MongoDB schemas
│   ├── routes/          # API endpoints
│   ├── controllers/     # Business logic
│   └── utils/           # Helpers & middleware
└── README.md
⚡ Getting Started
1️⃣ Clone the Repository
git clone https://github.com/anisha0404/social-media-mern.git
cd social-media-mern

2️⃣ Install Dependencies
Frontend:
cd client
npm install

Backend:
cd server
npm install

3️⃣ Setup Environment Variables

Create .env files in both client and server with the following:

Server (/server/.env)
MONGO_URI=your_mongodb_connection_string
CLERK_SECRET_KEY=your_clerk_secret_key
IMAGEKIT_PUBLIC_KEY=your_imagekit_public_key
IMAGEKIT_PRIVATE_KEY=your_imagekit_private_key
INNGEST_API_KEY=your_inngest_api_key
PORT=5000

Client (/client/.env)
VITE_CLERK_PUBLISHABLE_KEY=your_clerk_publishable_key
VITE_BACKEND_URL=http://localhost:5000

4️⃣ Run the Application
Backend:
cd server
npm run dev

Frontend:
cd client
npm run dev

🌍 Deployment

Frontend: Deploy React app on Vercel / Netlify

Backend: Deploy Node.js app on Render / Railway / Heroku

Database: Use MongoDB Atlas

Media Storage: Setup ImageKit

Auth: Configure Clerk domains in dashboard
