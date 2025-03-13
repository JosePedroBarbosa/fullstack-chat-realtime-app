# ✨ Full Stack Realtime Chat App ✨

This repository contains a real-time chat application built using a modern full-stack development stack.

## Technologies Used

### Frontend
- **React**: Framework for building user interfaces.
- **Tailwind CSS**: Utility-first CSS framework for responsive design.
- **Daisy UI**: Component library built on top of Tailwind CSS for rapid UI development.

### Backend
- **Node.js**: JavaScript runtime for server-side programming.
- **Express**: Minimalist framework for web applications in Node.js.
- **WebSocket (Socket.io)**: Implementation for real-time communication between client and server.

### Database
- **MongoDB**: NoSQL database for storing user data and messages.

## Features

- User Authentication && Authorization with JWT
- Real-time messaging between users.
- Online user status
- Responsive interface for desktop and mobile devices.
- Message history persisted in the database.
- [Live Demo](https://fullstack-chat-realtime-app-u02h.onrender.com/)

## Installation

### Setup .env file

```js
MONGODB_URI=...
PORT=5001
JWT_SECRET=...

CLOUDINARY_CLOUD_NAME=...
CLOUDINARY_API_KEY=...
CLOUDINARY_API_SECRET=...

NODE_ENV=development
```

### Build the app

```shell
npm run build
```

### Start the app

```shell
npm start
```
