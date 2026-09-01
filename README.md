# Blog App

A MERN-stack blogging application — posts, categories, user accounts and
authentication, with image uploads for post covers/profile photos.

## Tech stack

- **Backend** (`api/`): Node.js, Express, MongoDB (Mongoose)
- **Frontend** (`client/`): React (Create React App), React Router

## Structure

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

## Running locally

```bash
cd api
npm install
npm start
```
Requires a `.env` with a MongoDB connection string (see `api/index.js` for
the expected variable name).

```bash
cd client
npm install
npm start
```
