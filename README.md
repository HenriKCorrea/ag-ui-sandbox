# CopilotKit <> Microsoft Agent Framework (Python)

This is a starter template for building CopilotKit experiences using the [Microsoft Agent Framework](https://aka.ms/agent-framework). It ships with a Next.js UI and a FastAPI server that exposes a Microsoft Agent Framework agent over the AG-UI protocol, so you can study and customize both sides of the stack.

For better development experience, frontend and backend were split into separate projects.
This project is the Next.js frontend.

## Prerequisites

- Node.js 20+ 
- pnpm

## Getting Started

1. Install dependencies using package manager:

   ```bash
   # Using pnpm
   pnpm install
   ```

2. Start the development server:

   ```bash
   pnpm dev
   ```

   This will start the UI server.
   You must also start the agent backend following its README instructions.

## Available Scripts

The following scripts can also be run using your preferred package manager:

- `dev` – Starts both UI and agent servers in development mode
- `dev:debug` – Starts development servers with debug logging enabled
- `build` – Builds the Next.js application for production
- `start` – Starts the production server
- `lint` – Runs ESLint for code linting

## Project Structure

The main UI component is in `src/app/page.tsx`. You can:

- Modify the theme colors and styling
- Add new frontend actions
- Customize the CopilotKit sidebar appearance

## Framework Documentation

- [CopilotKit Documentation](https://docs.copilotkit.ai) – Explore CopilotKit’s capabilities
- [Next.js Documentation](https://nextjs.org/docs) – Learn about Next.js features and API

## License

This project is licensed under the MIT License – see the LICENSE file for details.
