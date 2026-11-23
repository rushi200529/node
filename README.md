# Simple Node.js App

A simple Express.js application that serves a welcome page and a health check endpoint.

## Requirements

- Node.js
- npm

## Installation

```bash
cd node_using_pm2
npm install
```

## Run the Application

```bash
npm start
```

The application runs on `http://localhost:3000` by default.

To use a different port:

```bash
PORT=8080 npm start
```

## Endpoints

- `/` - Returns the welcome message.
- `/health` - Returns `{"status":"ok"}` as JSON.
