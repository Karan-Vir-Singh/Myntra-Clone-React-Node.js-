🛍️ Myntra Clone (React + Node.js)

This project is a simple Myntra Clone built using React (Vite) for the frontend and Node.js + Express for the backend.

📁 Project Structure
myntra-clone-react-main/
│
└── myntra-clone-react-main/
    ├── backend/
    │   ├── app.js
    │   ├── items.json
    │   ├── package.json
    │
    └── frontend/
        ├── index.html
        ├── package.json
        ├── vite.config.js


🧰 Prerequisites

Make sure you have the following installed:
Node.js (v18 or above recommended)
npm (comes with Node)
VS Code (recommended)

Check installation:

node -v
npm -v


⚠️ Windows PowerShell Fix (IMPORTANT)

If you see this error while running npm install:
npm.ps1 cannot be loaded because running scripts is disabled

Fix:
Open PowerShell as Administrator

Run:
Set-ExecutionPolicy RemoteSigned -Scope CurrentUser
Type Y and press Enter
Restart VS Code


🚀 Backend Setup (Node + Express)

Open terminal in VS Code
Navigate to backend folder:
cd myntra-clone-react-main
cd backend

Install dependencies:
npm install

Start backend server:
node app.js
or
npm start

Backend will run on:
http://localhost:3000


🎨 Frontend Setup (React + Vite)

Open a new terminal
Navigate to frontend folder:
cd myntra-clone-react-main
cd frontend

Install dependencies:
npm install

Start frontend server:
npm run dev

Frontend will run on:
http://localhost:5173


🔗 Connecting Frontend & Backend

Ensure:
Backend is running on port 3000
Frontend API calls point to:
http://localhost:3000


If data is not loading, check API URLs in frontend files.
❗ Common Issues & Fixes
❌ Port already in use
npx kill-port 3000

❌ Module not found (e.g. express)
npm install

❌ Blank page

Make sure backend is running

Check browser console for errors


🛠️ Tech Stack
Frontend: React, Vite, JavaScript
Backend: Node.js, Express
Styling: CSS
Data: JSON


🙌 Contribution
Feel free to fork the repository and submit pull requests.


📌 Author
Karanvir
📌 Author

Karanvir
