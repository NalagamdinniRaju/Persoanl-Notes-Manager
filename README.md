I'll update the README with icons and include the correct GitHub repository link:

# 📝 Personal Notes Manager

<p align="center">
  <img src="https://img.shields.io/badge/React-18.2.0-blue?logo=react" alt="React"/>
  <img src="https://img.shields.io/badge/Node.js-18.x-green?logo=node.js" alt="Node.js"/>
  <img src="https://img.shields.io/badge/MongoDB-6.0-green?logo=mongodb" alt="MongoDB"/>
  <img src="https://img.shields.io/badge/License-MIT-yellow.svg" alt="License: MIT"/>
</p>

## ✨ Features

- 📝 Create, read, update, and delete notes
- 🏷️ Categorize notes with predefined categories
- 🔍 Search notes by title and description
- 🗂️ Filter notes by category
- 📱 Responsive design with smooth animations
- 🔔 Real-time feedback with toast notifications
- 🎨 Modern and intuitive user interface

## 🛠️ Tech Stack

### Frontend
- ⚛️ React.js
- 🎭 Framer Motion (for animations)
- 📦 React Icons
- 🔌 Axios (for API calls)
- 🍞 React Toastify
- 🎨 CSS3 for styling

### Backend
- 💻 Node.js
- 🚂 Express.js
- 🗄️ MongoDB
- 🔷 Mongoose
- 🔒 CORS

## 🚀 Installation

1. Clone the repository:
```bash
git clone https://github.com/NalagamdinniRaju/Persoanl-Notes-Manager.git
```

2. Install dependencies for both frontend and backend:
```bash
# Install frontend dependencies
cd frontend
npm install

# Install backend dependencies
cd ../backend
npm install
```

3. Create a `.env` file in the backend directory and add:
```
MONGODB_URL=your_mongodb_connection_string
PORT=5000
```

4. Start the application:
```bash
# Start backend server
cd backend
npm start

# Start frontend development server
cd frontend
npm start
```

## 📁 Project Structure

```
├── frontend/
│   ├── src/
│   │   ├── components/
│   │   │   ├── NoteCard/
│   │   │   ├── NoteForm/
│   │   │   ├── NoteList/
│   │   │   └── SearchBar/
│   │   ├── context/
│   │   │   └── NoteContext.js
│   │   └── App.js
│   └── package.json
│
└── backend/
    ├── config/
    │   └── db.js
    ├── models/
    │   └── Note.js
    ├── routes/
    │   └── notes.js
    ├── server.js
    └── package.json
```

## 🔌 API Endpoints

- 📥 `GET /api/notes` - Get all notes (with optional search and category filters)
- 📤 `POST /api/notes` - Create a new note
- 🔄 `PUT /api/notes/:id` - Update an existing note
- 🗑️ `DELETE /api/notes/:id` - Delete a note

## 📑 Available Categories

- 💼 Work
- 👤 Personal
- 📚 Study
- 🛍️ Shopping
- ❤️ Health
- 💰 Finance
- ✈️ Travel
- 💡 Ideas
- 🎯 Goals
- 🥘 Recipes
- 📖 Books
- 🎬 Movies
- 🎵 Music
- 📊 Projects
- 👥 Meetings
- 📅 Events
- 👨‍👩‍👧‍👦 Family
- 🎨 Hobbies
- 💻 Technology
- 📌 Others

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 👏 Acknowledgments

- [React Icons](https://react-icons.github.io/react-icons/) for the icon library
- [Framer Motion](https://www.framer.com/motion/) for smooth animations
- [MongoDB Atlas](https://www.mongodb.com/cloud/atlas) for database hosting

## 🔗 Links

- [GitHub Repository](https://github.com/NalagamdinniRaju/Persoanl-Notes-Manager.git)

## 👨‍💻 Author

- [Nalagamdinni Raju](https://github.com/NalagamdinniRaju)

