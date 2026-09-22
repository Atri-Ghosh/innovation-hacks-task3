# Task 3: Persistent Data Layer

Database integration using MongoDB and Mongoose ensuring robust persistence and relational modeling between Users, Projects, and Tasks.

## Database Schemas
- **User Schema**: Stores profile metadata and unique emails.
- **Project Schema**: Links projects to specific owner users.
- **Task Schema**: Relates tasks back to parent projects with status validation constraints (`todo`, `in-progress`, `done`).

## Setup Instructions
1. Install packages: `npm install mongoose express dotenv`
2. Configure your MongoDB connection string in `.env` (using `.env.example` as a template).
3. Run the application layer.