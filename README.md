# Next.js + Tailwind + Prisma Authentication Scaffold

This project is a Next.js application using the App Router, styled with Tailwind CSS, implementing user authentication with email/password, and includes various OpenAI-backed API routes.

## Features
- Next.js (App Router)
- Tailwind CSS for styling
- Prisma for database interactions
- Email/password authentication
- OpenAI API integration

## Getting Started

### Prerequisites
- Node.js
- npm
- A valid OpenAI API key

### Installation
1. Clone the repository:
   ```bash
   git clone https://github.com/hejsunway/admin-automation-agent.git
   cd admin-automation-agent
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Set up the environment variables:
   Copy `.env.example` to `.env` and fill in the required values.
   ```bash
   cp .env.example .env
   ```
4. Generate the Prisma client:
   ```bash
   npm run prisma:generate
   ```
5. Run database migrations:
   ```bash
   npm run prisma:migrate
   ```
6. Start the development server:
   ```bash
   npm run dev
   ```

## API Routes
- `/api/auth/signup` - Creates a new user account.
- `/api/auth/login` - Authenticates a user and returns a session cookie.
- `/api/ai/email-draft` - Generates a draft email using OpenAI.
- `/api/ai/meeting-summary` - Creates a summary for a meeting using OpenAI.
- `/api/ai/invoice-extract` - Extracts invoice data using OpenAI.

## Author
- hejsunway

---
