# 🕵️‍♂️ RepoScout – A Lightweight GitHub Explorer

**RepoScout** is a fully functional mini version of GitHub built using the **MERN stack**. It helps developers quickly discover public repositories, explore trending projects by tech stack, and even clone them — all in a clean, distraction-free UI.

🔗 

---

## 🚀 Tech Stack

- **Frontend**: React.js
- **Backend**: Node.js + Express.js
- **Database**: MongoDB (MongoDB Atlas)
- **Authentication**: GitHub OAuth via Passport.js
- **API Integration**: GitHub REST API

---

## ✨ Key Features

- 🔐 **GitHub Login**  
  Sign up / log in securely using your GitHub account via OAuth powered by Passport.js.

- 🔎 **User Search**  
  Enter any GitHub username and instantly fetch their public repositories.

- 📦 **Repository Info**  
  View repo details like:
  - ⭐ Stars
  - 🍴 Forks
  - 📅 Created At
  - 🔗 Clone Repo directly

- 🧮 **Filtering Options**  
  Filter repositories by:
  - Most starred
  - Most recent
  - Most forked

- 🌍 **Explore Section (The Game Changer)**  
  Discover trending, highly viewed, or most liked repositories filtered by tech stack like:
  - React
  - Node.js
  - Python
  - and more...

  GitHub doesn’t give you tech-wise discovery this easily — but RepoScout does, straight-up 🔍⚡

---

## 💡 Why RepoScout?

- 🎯 **Time Saver for Devs**  
  No more endless GitHub scrolling or googling to find good projects — everything's curated.

- 🧠 **Built with Practical Devs in Mind**  
  Focused repo discovery for contribution or inspiration without the GitHub overwhelm.

- 🧼 **Beginner-Friendly UI**  
  Clean, minimal, and distraction-free — built to help developers find what they need, fast.

---

## 🧑‍💻 Getting Started Locally

### 1. Clone the Repo

```bash
git clone https://github.com/Darshanchavan29/reposcout.git
cd reposcout
```

### 2. Install Dependencies

#### For Backend

```bash
cd server
npm install
```

#### For Frontend

```bash
cd client
npm install
```

### 3. Add `.env` Files

Create environment variable files for both `client` and `server` with GitHub OAuth keys and MongoDB URI.

```env
// server/.env
GITHUB_CLIENT_ID=your_client_id
GITHUB_CLIENT_SECRET=your_client_secret
MONGO_URI=your_mongo_uri
SESSION_SECRET=your_session_secret
```

### 4. Run App

```bash
# In /server
npm start

# In /client (new terminal)
npm start
```

Visit [http://localhost:3000](http://localhost:3000) to explore 🎉

---

## 🛠️ Deployment

You can deploy RepoScout on platforms like:

- **Frontend**: Vercel or Netlify
- **Backend**: Render, Railway, or Heroku
- **Database**: MongoDB Atlas (Cloud-hosted)

---

## 📚 Learn More

- [GitHub REST API Docs](https://docs.github.com/en/rest)
- [Passport.js GitHub Strategy](http://www.passportjs.org/packages/passport-github/)
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas)
- [Express.js](https://expressjs.com/)
- [React.js Docs](https://reactjs.org/)

---



