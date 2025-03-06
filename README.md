# API REST Rocketseat

This project is an API for handling transactions, built with Fastify, Knex, and SQLite.

## Features

- Create, list, and view transaction summaries
- Session-based security using cookies
- TypeScript for type safety

## Setup

1. **Install Dependencies:**

   ```bash
   npm install
   ```

2. **Configure Environment Variables:**

   Create a `.env` file based on your requirements. You must at least set the `DATABASE_URL` variable.

3. **Run Migrations:**

   ```bash
   npm run knex migrate:latest
   ```

4. **Start the Development Server:**

   ```bash
   npm run dev
   ```

## Linting

Ensure code quality by running:

```bash
npm run lint
npm run lint:fix
```

## Notes

- The project uses SQLite for database storage; the database file is located as specified in your configuration.
- For more information about how the API works, inspect the code in the `src` folder.

## License

ISC
