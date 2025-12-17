# 📝 Todo List API

A complete REST API for task management with authentication

## 🛠️ Technologies
- Node.js + Express
- TypeScript
- PostgreSQL + Prisma
- JWT Authentication
- Docker

## 🚀 Quick Setup

```bash
# Clone repository
git clone https://github.com/yourusername/todo-api.git

# Install dependencies
npm install

# Set up environment
cp .env.example .env

# Set up database
docker-compose up -d

# Run migrations
npx prisma migrate dev

# Run project
npm run dev
