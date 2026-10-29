# Wanderlust Server

Express and MongoDB API for the Wanderlust travel application.

## Requirements

- Node.js
- A MongoDB connection string

## Setup

1. Install dependencies with `npm install`.
2. Create a `.env` file and set `MONGODB_URI` and `CLIENT_URL`.
3. Start the API with `npm start` (or `npm run dev` for watch mode).

The API listens on port 8000. Destination and booking routes are defined in `index.js`.
