# Connected 💬

A modern WhatsApp-like messaging application with sky blue theme, built with React, Node.js, and PostgreSQL.

## Features ✨

### Core Messaging
- 💬 1-to-1 chats with other Connected users
- 👥 Group chats
- 🔵 Online/offline status
- ✓ Sent / delivered / read indicators
- 🗑️ Delete messages

### Media & Sharing
- 🎙️ Voice messages
- 📷 Photos and videos
- 📎 File sharing
- 😊 Emoji support

### User Features
- 📱 Phone-number or username accounts
- 👤 Profiles and profile pictures
- 🔍 Search chats and users
- 🟢 24-hour Status/Stories

### Safety & Privacy
- 🔒 Block/report users
- ⚙️ Privacy and notification settings
- 🔔 Push notifications

### Admin
- 🛡️ Admin dashboard for managing accounts, reports, blocks and suspensions

### Backend
- ☁️ Real backend/database (PostgreSQL)
- Real-time WebSocket communication
- JWT authentication
- File upload handling

## Tech Stack

### Frontend
- React 18+
- TypeScript
- Tailwind CSS (Sky Blue Theme)
- Socket.io client
- React Query
- Redux Toolkit

### Backend
- Node.js + Express
- PostgreSQL
- Socket.io
- JWT Authentication
- Multer (File uploads)
- Redis (Caching & Sessions)

### Deployment
- Docker support
- AWS S3 for file storage
- Heroku ready

## Project Structure

```
Connected/
├── frontend/              # React application
│   ├── src/
│   │   ├── components/   # React components
│   │   ├── pages/        # Page components
│   │   ├── hooks/        # Custom hooks
│   │   ├── services/     # API services
│   │   ├── store/        # Redux store
│   │   ├── styles/       # Tailwind styles
│   │   └── App.tsx
│   └── package.json
├── backend/              # Node.js/Express server
│   ├── src/
│   │   ├── controllers/  # Route controllers
│   │   ├── models/       # Database models
│   │   ├── routes/       # API routes
│   │   ├── middleware/   # Custom middleware
│   │   ├── utils/        # Utility functions
│   │   ├── socket/       # WebSocket handlers
│   │   └── server.ts
│   └── package.json
├── docker-compose.yml
├── .env.example
└── README.md
```

## Getting Started

### Prerequisites
- Node.js 16+
- PostgreSQL 12+
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/mcmeddy05/Connected.git
   cd Connected
   ```

2. **Setup Backend**
   ```bash
   cd backend
   npm install
   cp .env.example .env
   npm run migrate
   npm run dev
   ```

3. **Setup Frontend**
   ```bash
   cd ../frontend
   npm install
   npm start
   ```

4. **Access the app**
   - Frontend: http://localhost:3000
   - Backend: http://localhost:5000

## Environment Variables

See `.env.example` files in both frontend and backend directories.

## API Documentation

Full API documentation coming soon...

## Contributing

1. Create a feature branch (`git checkout -b feature/AmazingFeature`)
2. Commit changes (`git commit -m 'Add AmazingFeature'`)
3. Push to branch (`git push origin feature/AmazingFeature`)
4. Open a Pull Request

## License

This project is licensed under the MIT License - see LICENSE file for details.

## Author

**mcmeddy05** - [GitHub](https://github.com/mcmeddy05)

---

**Status**: 🚀 In Development - First Production Version Coming Soon!
