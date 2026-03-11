# Full-Stack Social Media Application

A professional, full-stack social media application inspired by Threads, built using the MERN stack. This project features real-time communication, secure authentication, and a responsive modern UI.

## Tech Stack

### Frontend
- **React.js & Vite**: Modern frontend library and build tool for a fast development experience.
- **Chakra UI**: Component library used for a sleek, accessible, and responsive user interface.
- **Recoil**: State management library for handling global application state efficiently.
- **Socket.io-client**: Enables real-time, bi-directional communication for messaging and notifications.
- **Framer Motion**: Powerful animation library for smooth UI transitions and micro-interactions.

### Backend
- **Node.js & Express**: Scalable server-side environment and web framework.
- **MongoDB & Mongoose**: NoSQL database and Object Data Modeling (ODM) for flexible data management.
- **Socket.io**: Real-time engine for instant messaging and live updates.
- **Cloudinary**: Cloud-based service for optimized image storage and delivery.
- **JWT (JSON Web Tokens)**: Secure, stateless authentication and authorization.

## Key Features
- **Real-Time Messaging**: Instant chat functionality with support for image attachments and read/unread status.
- **Comprehensive Social Interaction**: Post creation, deletion, liking, and commenting system.
- **User Engagement**: Follow/unfollow system with real-time notification sounds.
- **Account Management**: Profile customization and account freezing functionality.
- **Modern UI/UX**: Dark and light mode support with a fully responsive layout across all device types.

## Installation and Setup

### 1. Prerequisites
Ensure you have the following installed:
- Node.js (v16.x or higher)
- npm or yarn
- A MongoDB Atlas account
- A Cloudinary account

### 2. Environment Configuration
Create a `.env` file in the root directory and provide the following credentials:
```env
PORT=5000
MONGO_URI=your_mongodb_uri
JWT_SECRET=your_jwt_secret
CLOUDINARY_CLOUD_NAME=your_cloud_name
CLOUDINARY_API_KEY=your_api_key
CLOUDINARY_API_SECRET=your_api_secret
```

### 3. Install Dependencies
Run the following command in the root directory to install both backend and frontend dependencies:
```bash
npm run build
```
*Note: This script installs backend dependencies, frontend dependencies, and generates the production-ready frontend build.*

## How to Run

### Development Mode
For a hot-reloading development environment:
```bash
npm run dev
```

### Production Mode
To host the optimized production build:
```bash
npm start
```

## Project Directory Structure
- `/backend`: Express server, MongoDB models, API routes, and Socket.io logic.
- `/frontend`: React application, UI components (Chakra UI), state management (Recoil), and styling.
- `/frontend/dist`: Static assets for the production-ready frontend.
