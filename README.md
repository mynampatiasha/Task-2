# 📝 Blog App

`MERN` `Node.js` `Express` `MongoDB` `React`

> A full MERN-stack blogging platform.

## What is this?

A MERN-stack blogging application — posts, categories, user accounts and
authentication, with image uploads for post covers/profile photos.

## ✨ Features

- ✍️ Create, edit, and browse blog posts
- 🏷️ Post categories
- 🔐 User accounts and authentication
- 🖼️ Image uploads for covers and profile photos

## 🛠️ Tech Stack

- **Backend** (`api/`): Node.js, Express, MongoDB (Mongoose)
- **Frontend** (`client/`): React (Create React App), React Router

## 📁 Structure

```
api/
  models/    # User.js, Post.js, Category.js
  routes/    # auth.js, users.js, posts.js, categories.js
  images/    # uploaded post/profile images
  index.js   # Express app entry point

client/
  src/App.js    # app root
  src/index.js  # React entry point
```

## 🚀 Running Locally

```bash
cd api && npm install && npm start
```
Requires a `.env` with a MongoDB connection string.

```bash
cd client && npm install && npm start
```
