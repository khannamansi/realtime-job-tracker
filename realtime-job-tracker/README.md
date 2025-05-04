# 🛠 Realtime Job Tracker – AI Enhanced

A full-stack real-time job application tracker with AI integration to generate resume tips and interview questions. Built with React frontend and two interchangeable backends: Node.js (Express) and Python (FastAPI).

## 🌐 Tech Stack

- **Frontend:** React + Tailwind + Axios
- **Backend 1:** Node.js + Express + PostgreSQL + Socket.IO
- **Backend 2:** Python + FastAPI + PostgreSQL + WebSockets
- **AI Integration:** OpenAI API (GPT)
- **Authentication:** JWT
- **Deployment Options:** Vercel (frontend), Render/Railway (backend), Supabase/PlanetScale (DB)

## 📦 Setup Instructions

### 🔧 Prerequisites

- Node.js (for frontend and Node backend)
- Python 3.9+ (for FastAPI backend)
- PostgreSQL
- OpenAI API key (optional for AI features)

## 🚀 Getting Started

### 1. Clone the Repo

```bash
git clone https://github.com/your-username/realtime-job-tracker.git
cd realtime-job-tracker
```

### 2. Setup Environment Variables

#### Frontend

```bash
cd frontend
cp .env.example .env
npm install
npm start
```

#### Node.js Backend

```bash
cd backend-node
cp .env.example .env
npm install
npm run dev
```

#### FastAPI Backend

```bash
cd backend-python
cp .env.example .env
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows
pip install -r requirements.txt
uvicorn main:app --reload
```

### 3. PostgreSQL DB

Create a PostgreSQL database and update `.env` files with:

```env
DATABASE_URL=postgresql://user:password@localhost:5432/jobtracker
```

### 🧠 Optional: Enable OpenAI API

For resume and interview suggestions:

```env
OPENAI_API_KEY=your-api-key
```

## 🛠 Todo

- [ ] Implement Realtime Job Status (Socket.IO/WebSocket)
- [ ] Add GPT-powered resume suggestions
- [ ] Create collaborator sharing feature
- [ ] Add analytics dashboard

## 🙌 Contributing

PRs welcome! This is a learning-focused project. Feel free to fork and experiment.

## 📄 License

MIT License
