
# Vibe Coding

Vibe Coding is a modern, full-stack web application designed to provide a collaborative and interactive coding experience. Built with Next.js, Prisma, and TypeScript, it features project management, real-time code editing, and a beautiful UI.

## Features
- Project and file explorer
- Real-time code editing
- User authentication (Clerk)
- Usage analytics
- Modern UI components
- Integration with OpenAI API

## Tech Stack
- Next.js
- TypeScript
- Prisma (PostgreSQL)
- Clerk (Authentication)
- Tailwind CSS
- OpenAI API

## Getting Started
1. Clone the repository:
	```bash
	git clone https://github.com/ramashishyadav108/Vibe-coding.git
	cd Vibe-coding
	```
2. Install dependencies:
	```bash
	npm install
	```
3. Set up your environment variables in a `.env` file (see `.env.example`).
4. Run database migrations:
	```bash
	npx prisma migrate deploy
	```
5. Start the development server:
	```bash
	npm run dev
	```

## Folder Structure
- `src/` - Main application source code
- `prisma/` - Prisma schema and migrations
- `public/` - Static assets
- `components/` - Reusable UI components

## License
MIT
