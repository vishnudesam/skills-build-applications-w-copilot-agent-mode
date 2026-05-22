# OctoFit Tracker

A modern multi-tier fitness tracking application built with GitHub Copilot Agent Mode.

## Architecture

- **Frontend**: React 19 with Vite (Port 5173)
- **Backend**: Node.js + Express + TypeScript (Port 8000)
- **Database**: MongoDB (Port 27017)

## Getting Started

### Prerequisites
- Node.js 18+
- MongoDB running locally

### Frontend Setup

```bash
cd octofit-tracker/frontend
npm install
npm run dev
```

Frontend will be available at `http://localhost:5173`

### Backend Setup

```bash
cd octofit-tracker/backend
npm install
npm run dev
```

Backend will be available at `http://localhost:8000`

### MongoDB Setup

Ensure MongoDB is running on `localhost:27017`

## Project Structure

```
octofit-tracker/
├── frontend/          # React 19 + Vite application
│   ├── src/
│   ├── package.json
│   ├── vite.config.ts
│   └── tsconfig.json
└── backend/           # Express + TypeScript application
    ├── src/
    ├── package.json
    └── tsconfig.json
```

## Development

Both frontend and backend support TypeScript for type safety and better development experience.
