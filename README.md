# Task Manager AWS

This project is a **full-stack Task Manager** built with:

- **Backend:** AWS SAM + Node.js + TypeScript
- **Frontend:** React + TypeScript
- **Local development:** AWS SAM CLI + Docker

The backend is fully serverless and can be run locally or deployed to AWS.

---

# Task Manager Backend (AWS SAM + TypeScript)

This backend is a **serverless API** built with **AWS SAM**, **Node.js 20**, and **TypeScript**.  
It can be run **locally** using AWS SAM CLI or **deployed to AWS**.

---

## Prerequisites

Make sure you have the following installed:

- Node.js (v18 or higher)
- Docker
- AWS SAM CLI

Verify installations:

```bash
node -v
docker --version
sam --version
```

## Setup

```bash
cd backend
npm install
```

## Build

```bash
npm run build
```

## Run Locally with AWS SAM

```bash
sam build
sam local start-api -p 3001

```

## Test the API

```bash
curl http://localhost:3001/ping
```

---

# Task Manager Frontend (React + TypeScript)

This frontend is built with **React + TypeScript** and is intended to consume the backend API (running locally via AWS SAM or deployed to AWS).

---

## Prerequisites

Make sure you have:

- Node.js (v18 or higher)
- npm

Verify:

```bash
node -v
npm -v
```

# Setup

```bash
cd frontend
npm install
```

## Run Frontend Locally

```bash
npm run dev

```
