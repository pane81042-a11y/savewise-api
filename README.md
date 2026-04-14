# SaveWise API

SaveWise API is the backend service for the SaveWise savings tracker platform.

It manages savings goals, deposit tracking, dashboard summaries, filtering, sorting, and user profile functionality through protected REST API endpoints.

## Features

- Full CRUD for savings goals
- Full CRUD for deposits
- Dashboard summary calculations
- Goal progress tracking
- Goal filtering and sorting
- Protected routes with token-based authentication
- Full CRUD for user profile data
- MongoDB persistence
- CORS configuration for frontend integration

## Tech Stack

- Node.js
- Express
- MongoDB
- Mongoose
- JWT authentication middleware
- Validation and security middleware

## Getting Started

### 1. Clone the repository
```bash
git clone <your-savewise-api-repo-url>
cd savewise-api
```
### 2. Install dependencies
```bash
npm install
```
### 3. Create environment variables
- Create a .env file and configure the required environment variables.
- Example:
```env
PORT=5000
MONGODB_URI=your_mongodb_connection_string
JWT_SECRET=your_jwt_secret
CLIENT_URL=http://localhost:5173
AUTH_SERVICE_URL=http://localhost:5001
```
### 4. Start the development server
```bash
npm run dev
```
### Scripts
```bash
npm run dev
npm run start
npm run seed
npm run lint
```

## API Responsibilities
This service is focused on application domain logic such as goals, deposits, summaries, and profile-related functionality.

## Related Repositories
- SaveWise Client
- SaveWise Auth Service
- SaveWise Shared
- SaveWise UI
- SaveWise Infra
