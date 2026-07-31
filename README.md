# test-project

A Node.js web application built with **TypeScript** and **Next.js**.

## Tech Stack

| Layer | Technology |
|-------|------------|
| Runtime | Node.js |
| Language | TypeScript |
| Framework | Next.js (App Router) |
| Package manager | npm |

## Prerequisites

- [Node.js](https://nodejs.org/) (LTS recommended)
- npm

## Getting Started

Install dependencies:

```bash
npm install
```

Copy environment variables and fill in your values:

```bash
cp .env.example .env.local
```

Start the development server (after Next.js is configured):

```bash
npm run dev
```

Open [http://localhost:3000](http://localhost:3000) in your browser.

## Project Structure

```
ai/
  cursor.md       # AI assistant guidelines
app/              # Next.js App Router pages and layouts
components/       # Shared React components
lib/              # Utilities, helpers, and shared logic
public/           # Static assets
```

## Environment Variables

This project uses [dotenv](https://github.com/motdotla/dotenv) for environment configuration. Store local secrets in `.env.local` and never commit that file.

## Scripts

| Command | Description |
|---------|-------------|
| `npm install` | Install dependencies |
| `npm run dev` | Start the development server |
| `npm run build` | Build for production |
| `npm start` | Run the production server |
| `npm test` | Run tests |

> **Note:** Next.js scripts will be available once the framework is initialized.

## License

ISC
