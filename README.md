# Zoom
A full stack video conferencing web application.
Video Conferencing Web App

A full-stack video conferencing app built with Next.js (React), Node.js + Express + Socket.IO, WebRTC, and MongoDB.

✨ Features

Create or join rooms

Video & audio calls (multi-user)

Text chat and screen sharing

Mute/unmute mic, toggle camera

Simple & ready for hackathons 

🔧 Setup
1. Clone repo
git clone <your-repo-url>
cd <repo-folder>

2. Start backend
cd server
npm install
cp .env.example .env   # Add MongoDB URI + keys
npm run dev

3. Start frontend
cd ../client
npm install
cp .env.example .env.local
npm run dev

4. Open in browser

👉 http://localhost:3000

 Deployment Notes

Use Vercel or Netlify for frontend

Use Render or Heroku for backend

Enable HTTPS (required for mic/cam)

Add a TURN server for reliable calls

📝 License

MIT License
