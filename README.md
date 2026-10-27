# PrepPilot — AI Interview Preparation Platform

PrepPilot is an ongoing full-stack project that helps candidates prepare for interviews using AI-generated questions, flashcards, and preparation schedules tailored to job descriptions and company research.

## Tech Stack

**Backend:** Node.js, Express.js, JavaScript, MongoDB, Mongoose, REST APIs

**AI:** Google Gemini API

**Frontend (In Progress):** Next.js, React, TypeScript, Tailwind CSS

## Features

- AI-powered interview question and flashcard generation
- Company research and job-description requirement extraction
- Interview preparation schedules and coverage analysis
- REST APIs with authentication and authorization
- Session-based authentication, input validation, rate limiting, and CORS protection
- Modular backend service architecture

## Project Status

- **Backend:** Implemented; automated tests available.
- **Frontend:** Currently in development.

## Getting Started

### Backend

```bash
npm install
```

Configure the required environment variables in a local `.env` file using `.env.example` as a reference.

Start the backend using the command configured in `package.json`, for example:

```bash
npm run dev
```

### Frontend

The frontend is being developed separately within the `frontend/` directory. Refer to its `package.json` and configuration files for setup and run instructions.

## Security

Never commit `.env` files, API keys, database credentials, or session secrets. Use environment variables for sensitive configuration.
