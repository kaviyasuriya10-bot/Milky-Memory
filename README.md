# MilkyMemory — Node.js + Express

Complete frontend + backend. No Python and no MySQL.

## Run
1. Install Node.js 18+.
2. Run `npm install`.
3. Copy `.env.example` to `.env` and set `SESSION_SECRET`.
4. Run `npm start`.
5. Open http://localhost:5000

Data is stored in `data/users.json` and `data/memories.json`. Passwords are bcrypt-hashed and memory routes are isolated by authenticated user ID.
