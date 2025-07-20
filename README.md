# LetMeAsk

LetMeAsk is a full stack web application that allows users to create interactive rooms and submit questions through audio, which are then transcribed and processed using Gemini AI to generate questions for discussion or learning purposes.

👉 [Versão em Português](./README-pt.md)

## 🚀 Tech Stack

**Frontend:**
- React
- TypeScript
- React Router
- Axios

**Backend:**
- Node.js
- Express
- Prisma (ORM)
- PostgreSQL
- Gemini AI Integration

## ✨ Features

- Create rooms dynamically
- Audio recording and upload
- Transcription and question generation using Gemini AI
- View all rooms and their questions
- Responsive UI for room and question management

## 💻 Getting Started

### Prerequisites

- Node.js and npm
- PostgreSQL

### Clone the repository

```bash
git clone https://github.com/gabrielsouzacampos/LetMeAsk.git
cd LetMeAsk
```

### Backend Setup

```bash
cd server
npm install
npx prisma generate
npx prisma migrate dev
npm run dev
```

### Frontend Setup

```bash
cd client
npm install
npm run dev
```

## 📸 Preview
<p style="display: flex; justify-content: space-evenly; align-items: start;">
  <img src="./images/Home.png" alt="Home Page" width="40%"/>
  <img src="./images/Room.png" alt="Room Page" width="40%"/>
</p>
