# Go_Ride Project

## Project Setup and Run Instructions

This project consists of two main parts:

1. **Backend**: A Node.js server for handling API requests and managing the database.
2. **Frontend**: A React-based client application for user interaction.

### Prerequisites

Ensure you have the following installed on your system:

- Node.js (v16 or later)
- npm (Node Package Manager)

### Backend Setup

1. Navigate to the `Backend` directory:
   ```bash
   cd Backend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the backend server:
   ```bash
   npm start
   ```

### Frontend Setup

1. Navigate to the `Frontend` directory:
   ```bash
   cd Frontend
   ```
2. Install dependencies:
   ```bash
   npm install
   ```
3. Start the development server:
   ```bash
   npm run dev
   ```

### Project Structure

- **Backend**:
  - `controllers/`: Contains logic for handling API requests.
  - `db/`: Database connection and configuration.
  - `middlewares/`: Middleware functions for request processing.
  - `models/`: Mongoose models for database schemas.
  - `routes/`: API route definitions.
  - `services/`: Business logic and helper functions.
- **Frontend**:
  - `src/components/`: Reusable React components.
  - `src/context/`: Context API for state management.
  - `src/pages/`: Page components for routing.

### Dependencies

#### Backend

- `axios`
- `bcrypt`
- `cookie-parser`
- `cors`
- `crypto`
- `dotenv`
- `express`
- `express-validator`
- `jsonwebtoken`
- `mongoose`
- `socket.io`

#### Frontend

- `@gsap/react`
- `@react-google-maps/api`
- `@tailwindcss/vite`
- `axios`
- `gsap`
- `react`
- `react-dom`
- `react-router-dom`
- `remixicon`
- `socket.io-client`

### Running the Project

1. Start the backend server as described in the Backend Setup section.
2. Start the frontend development server as described in the Frontend Setup section.
3. Open your browser and navigate to the frontend's development server URL (usually `http://localhost:5173`).
