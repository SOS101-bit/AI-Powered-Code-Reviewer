# AI-Powered Code Reviewer

This project is an AI-powered code review platform with a React frontend and a Node.js/Express backend. It allows users to submit code for automated review and receive feedback based on good coding practices powered by AI.

## Features
- Submit code for review (copy and paste the code in the code editor and then press the "Review" Button)
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

## Demo
  **Watch the demo video:** [Click here to view](https://drive.google.com/file/d/15hOrPRCNtlPZhmJBlFMHM6U0kP8TJKeY/view?usp=sharing)


## Author
SOS101-bit (Sourav Sahoo)
