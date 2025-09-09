# Store Rating App - Backend (Express + MySQL + Sequelize)

## Quick Start
```bash
cd backend
cp .env.example .env
#.env with your MySQL creds
npm install
npm run dev
```

## Create DB
Create a MySQL database with the name in `.env` (DB_NAME). Sequelize will sync tables automatically on server start.

## Roles
- `admin`, `user`, `owner`