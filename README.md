# Node Starter

This is a Node.js starter project with TypeScript, ESLint, Prettier, Zod, T3-Env, Husky, and Nodemon.

## Getting Started

1. Clone the repository
2. Install dependencies with `npm install`
3. Start the development server with `npm run dev`

## Scripts

- `lint`: Run ESLint on the codebase
- `lint:fix`: Run ESLint and automatically fix problems
- `format`: Run Prettier on the codebase
- `format:fix`: Run Prettier and automatically format code
- `build`: Compile TypeScript to JavaScript
- `start`: Start the application (make sure to build first)
- `dev`: Start the development server with hot-reloading
- `prepare`: Set up Husky for git hooks

## Environment Variables

Environment variables are managed with T3-Env and Zod. They are defined in `env.ts` and loaded from the system environment variables.

## Code Formatting

This project uses ESLint and Prettier for code formatting and linting. The configuration for these tools is found in `eslint.config.js` and `prettier.config.js` respectively.
