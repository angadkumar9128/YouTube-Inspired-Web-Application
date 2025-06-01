
# <a href="https://deepwiki.com/angadkumar9128/YouTube-Inspired-Web-Application"><img src="https://deepwiki.com/badge.svg" alt="Ask DeepWiki"></a>


# 🎬 YouTube-Inspired Web Application

A full-stack video-sharing platform inspired by YouTube. This project allows users to upload, view, like, and comment on videos. It includes user authentication, dynamic video rendering, and a modern, responsive UI.

## 📌 Project Overview

This project aims to replicate the core features of YouTube using the MERN (MongoDB, Express.js, React.js, Node.js) stack. It provides functionalities such as video uploading, playback, comments, likes/dislikes, and channel subscriptions.

## 🚀 Key Features

- 🔐 User Registration and Authentication
- 📤 Upload Videos with Title and Description
- 🎥 Watch Videos in an Embedded Player
- ❤️ Like / 👎 Dislike Functionality
- 💬 Comment on Videos
- 🔍 Search Videos by Title
- 📺 View Channels and Subscribe
- 🖥️ Responsive UI

## 🛠️ Tech Stack

**Frontend:**
- React.js
- React Router
- CSS / TailwindCSS or Material UI (depending on the branch)

**Backend:**
- Node.js
- Express.js
- Multer (for file uploads)

**Database:**
- MongoDB
- Mongoose

**Other Tools:**
- Git & GitHub
- Nodemon (for development)
- Postman (for testing APIs)

## 📁 Folder Structure

YouTube-Inspired-Web-Application/
├── client/ # React frontend
│ ├── public/
│ └── src/
│ ├── components/
│ ├── pages/
│ └── App.js
├── server/ # Express backend
│ ├── controllers/
│ ├── models/
│ ├── routes/
│ └── index.js
├── uploads/ # Uploaded video files
├── .gitignore
├── package.json
└── README.md


## 🧑‍💻 Getting Started

### Prerequisites

Make sure you have the following installed:
- Node.js
- npm or yarn
- MongoDB (local or cloud instance like MongoDB Atlas)

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/angadkumar9128/YouTube-Inspired-Web-Application.git
   cd YouTube-Inspired-Web-Application


Install server dependencies

cd server
npm install

Install client dependencies

cd ../client
npm install

Set up environment variables

Create a .env file in the server/ directory and add:

ini
MONGO_URI=your_mongodb_connection_string
PORT=5000

Run the backend

cd ../server
npm run dev
Run the frontend

cd ../client
npm start

Your app will be running at http://localhost:3000.

🧪 Usage Instructions
Register or login to your account.

Upload videos through the Upload button.

Browse the homepage or search for videos.

Click on a video to view it in the video player.

Like, dislike, or comment on the video.

Visit user profiles and subscribe to channels.

🤝 Contributing
Contributions are welcome!

Fork the repo

Create your feature branch: git checkout -b feature-name

Commit your changes: git commit -m "Added feature"

Push to the branch: git push origin feature-name

Open a Pull Request

📄 License
This project is open-source and available under the MIT License.

🙏 Acknowledgements
React

Node.js

MongoDB

Multer

Inspiration from YouTube's UI/UX design

Made with ❤️ by Angad Kumar
