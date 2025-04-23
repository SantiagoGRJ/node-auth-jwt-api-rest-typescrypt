# Node.js Authentication API with JWT and TypeScript

This project is a Node.js-based API that implements user authentication using JSON Web Tokens (JWT). It is built with TypeScript for type safety and Prisma ORM for database management.

## Features
- User authentication with JWT.
- Secure password hashing.
- Database integration using Prisma ORM.
- TypeScript for enhanced development experience.

## Prerequisites
- **Node.js**: Version 16 or higher.
- **npm**: Version 7 or higher.
- **Database**: PostgreSQL or compatible.

## Installation

1. **Clone the repository**:
   ```bash
   git clone https://github.com/SantiagoGRJ/node-auth-jwt-api-rest-typescrypt.git
   cd node-auth-jwt-api-rest-typescrypt
   ```

2. **Install dependencies**:
   ```bash
   npm install
   ```

3. **Set up environment variables**:
   - Copy the `.env.template` file to `.env`:
     ```bash
     cp .env.template .env
     ```
   - Update the `.env` file with your database credentials and other configurations.

4. **Set up the database**:
   - Run Prisma migrations to set up the database schema:
     ```bash
     npx prisma migrate dev
     ```

5. **Start the application**:
   - In development mode:
     ```bash
     npm run dev
     ```
   - In production mode:
     ```bash
     npm run build
     npm start
     ```

## Project Structure
- `src/`: Contains the main application code.
- `prisma/`: Contains Prisma schema and migration files.
- `.env.template`: Template for environment variables.
- `tsconfig.json`: TypeScript configuration file.

## Scripts
- `npm run dev`: Starts the application in development mode.
- `npm run build`: Compiles the TypeScript code to JavaScript.
- `npm start`: Runs the compiled JavaScript code in production mode.

## License
This project is licensed under the MIT License.