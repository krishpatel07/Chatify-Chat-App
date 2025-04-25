# Realtime Chat Application - Chatify 💬

## 🧾 Abstract:

The Realtime Chat Application is a full-stack web-based messaging system built using the MERN stack. It allows users to register, authenticate, and chat with other users in real time. The backend uses Socket.IO for bi-directional communication, enabling seamless live chat functionality. User authentication is handled securely using JWT, and file attachments are supported through Multer. The frontend is designed with Tailwind CSS and includes modern UI components from ShadCN, ensuring a responsive and engaging user experience across devices.

## 🚀 Features:

- Real-time messaging with Socket.IO
- JWT-based authentication
- Emoji picker support
- File uploads and downloads
- Responsive UI with Tailwind CSS
- Zustand for state management
- Axios for API communication
- Clean UI components via ShadCN

## 🛠️ Tech Stack:

**Frontend:**
- **Vite + React.js** – Provides the component-based architecture for building a dynamic and fast user interface.
- **Tailwind CSS** – Utility-first CSS framework used for designing responsive and attractive UI quickly.
- **ShadCN UI Components** – Pre-built, accessible, and customizable components built on Radix UI, used to enhance UI consistency and interactivity.
- **Zustand** – Lightweight and scalable state management tool for handling global and local state in React.
- **Emoji-picker** – Library for selecting and inserting emojis in messages, enhancing chat expressiveness.

**Backend:**
- **Node.js** – JavaScript runtime used to build scalable server-side applications.
- **Express.js** – Minimal and flexible Node.js web framework used to create RESTful APIs.
- **MongoDB (Mongoose)** – NoSQL database used to store user data, messages, and chat history, with Mongoose for object modeling.
- **Socket.IO** – Enables real-time, bi-directional communication between client and server for instant messaging.
- **Multer** – Middleware for handling file uploads (e.g., images, documents) to the server.
- **JSON Web Tokens (JWT)** – Used for secure authentication and maintaining user sessions.

### Setup .env file (on Server Side)

```js
PORT=8000
JWT_KEY="....."
ORIGIN="http://localhost:5173"
DATABASE_URL="YOUR MONGODB DATABASE LINK...."
```

### Setup Frontend

```shell
cd client
npm install
npm run dev
```
### Setup Backend

```shell
cd server
npm install
npm run dev
```

## 📸 Demo Screenshots

### User Login/Sigup Page:
![image](https://github.com/user-attachments/assets/e1f12a72-aaa0-4b97-9a12-4f52088fcf12)

### User Profile Setup:
![image](https://github.com/user-attachments/assets/2eb76087-4962-4f79-8bfe-31e8951ccc96)

### Chat HomePage:
![image](https://github.com/user-attachments/assets/594645de-96cb-4c42-91a3-04cc5a1db00e)

### Message Container:
![image](https://github.com/user-attachments/assets/3898f04d-93c4-4c19-8373-f381f7da60b4)

### Channels:
![image](https://github.com/user-attachments/assets/2f6412bd-560b-4520-b66f-eb4750350197)

## Authors
- [Krish Dobariya](https://github.com/krishpatel07)
- [Pavitra Virani](https://github.com/Virani-Pavitra)







