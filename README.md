# TypeScript Clean Architecture Project

This project is a TypeScript implementation of Clean Architecture principles.

## Project Structure

```
src/
├── domain/         # Domain layer (entities, value objects, interfaces)
├── usecases/       # Use cases (business logic)
├── interfaces/     # Interface adapters (repositories, controllers)
├── infrastructure/ # Infrastructure (database, external services)
├── controllers/    # Controllers (HTTP handlers)
└── main/          # Main application entry point
```

## Setup

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the development server:
   ```bash
   npm run dev
   ```

3. Build the project:
   ```bash
   npm run build
   ```

## Technologies Used

- TypeScript
- Express
- Clean Architecture
- Dependency Injection (tsyringe)
- Reflect Metadata
