# Advanced Spotify Clone

An all-in-one **social streaming hub** for music, podcasts, and real-time connections. This platform allows users to stream music, listen to podcasts, chat with other users, and share their listening experience.


---

## Features

1. **Music Streaming**
   - Stream your favorite tracks seamlessly.
2. **Podcast Streaming**
   - Discover and listen to podcasts.
3. **User Chats**
   - Real-time messaging with other users.
4. **Social Integration**
   - Share and explore what others are listening to.
5. **Playlists**
   - Create, share, and manage playlists.
6. **Responsive UI**
   - Works smoothly on all devices (desktop, mobile, tablet).

---

## Tech Stack

### Frontend
- **HTML5, CSS3, JavaScript**
- **React.js** (for building the UI)
- **Tailwind CSS** (for styling)

### Backend
- **Node.js** (server-side logic)
- **Express.js** (API creation)
- **Socket.IO** (real-time chat feature)

### Database
- **MongoDB** (data storage)

### Other Tools
- **Cloudinary** (media storage for images/audio)
- **Clerk** (authentication)

---

## Installation

Follow these steps to set up the project locally:

### Prerequisites
- Node.js installed (v14+)
- MongoDB set up locally or remotely
- Spotify Developer Account (API credentials)

### Steps
1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/advanced-spotify-clone.git
   cd advanced-spotify-clone
   ```
2. **Install Dependencies**
   ```bash
   npm install
   ```
3. **Environment Variables**
   Create a `.env` file in the root directory and add the following:
   ```plaintext
   PORT=5000
   MONGO_URI=<your_mongoDB_connection_string>
   JWT_SECRET=<your_jwt_secret>
   SPOTIFY_CLIENT_ID=<your_spotify_client_id>
   SPOTIFY_CLIENT_SECRET=<your_spotify_client_secret>
   CLOUDINARY_URL=<your_cloudinary_api_url>
   ```
4. **Start the Development Server**
   ```bash
   npm start
   ```
5. **Run the Frontend**
   - Navigate to the frontend directory (if separate).
   ```bash
   cd client
   npm start
   ```
6. Open `http://localhost:3000` in your browser.

---

## Usage
1. Sign up or log in to the platform.
2. Explore music and podcasts through the home page.
3. Start streaming music or listening to podcasts.
4. Chat with other users in real-time using the chat feature.
5. Create and manage playlists for your favorite content.
6. Share your current listening activities with friends.

