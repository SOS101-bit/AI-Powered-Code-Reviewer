# AI-Powered Code Reviewer

This project is an AI-powered code review platform with a React frontend and a Node.js/Express backend. It allows users to submit code for automated review and receive feedback based on good coding practices powered by AI.

## Features
- Submit code for review
- Receive AI-generated feedback
- Modern React frontend
- RESTful backend API

## Project Structure
- **Frontend/**: React app (Vite)
- **BackEnd/**: Node.js/Express server
- **AI/LLM/**: Gemini 2.5 Flash (Google's llm designed to handle 10000 lines of code)

---

## Setup Instructions

### Prerequisites
- Node.js (v16 or higher recommended)
- npm (comes with Node.js)

### 1. Clone the Repository
```sh
git clone https://github.com/SOS101-bit/AI-Powered-Code-Reviewer.git
cd AI-Powered-Code-Reviewer
```

### 2. Install Dependencies
#### Backend
```sh
cd BackEnd
npm install
```
#### Frontend
```sh
cd ../Frontend
npm install
```

### 3. Run the Applications
#### Start Backend Server
```sh
cd BackEnd
npm start
```
#### Start Frontend (Vite Dev Server)
```sh
cd ../Frontend
npm run dev
```

### 4. Access the App
- Frontend: [http://localhost:5173](http://localhost:5173) (default Vite port)
- Backend: [http://localhost:3000](http://localhost:3000) (default Express port)

---

## Customization
- Update backend logic in `BackEnd/src/`
- Update frontend UI in `Frontend/src/`

## Author
SOS101-bit (Sourav Sahoo)
