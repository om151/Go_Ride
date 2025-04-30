# Go_Ride Project

## Project Setup and Run Instructions

This project consists of two main parts:

1. **Backend**: A Node.js server for handling API requests and managing the database.
2. **Frontend**: A React-based client application for user interaction.

### Prerequisites

Ensure you have the following installed on your system:

- Node.js (v16 or later)
- npm (Node Package Manager)

### Cloning the Repository

1. Clone the repository:
   ```bash
   git clone https://github.com/om151/Go_Ride.git
   ```
2. Enter the project directory:
   ```bash
   cd Go_Ride
   ```

   ### Opening Terminals

   To run both frontend and backend servers simultaneously:

   1. Open two separate terminal windows
   2. Use one terminal for the backend server
   3. Use another terminal for the frontend server

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


### Running the Project

1. Start the backend server as described in the Backend Setup section.
2. Start the frontend development server as described in the Frontend Setup section.
3. Open your browser and navigate to the frontend's development server URL (usually `http://localhost:5173`).

### Using the Project

To fully experience the application, you need to create two different accounts:

1. **Captain Account**:
   - Open the application in one browser window
   - Click on "Register as Captain"
   - Fill in the required details

2. **User Account**:
   - Open the application in a different browser window
   - Click on "Register as User"
   - Fill in the required details
   - Start requesting rides

Note: Using separate browser windows ensures you can be logged in as both user types simultaneously.


### Requesting a Ride

1. **Set Locations**:
   - Enter your pickup location (must be within 2km of your current location)
   - Enter your destination
   - The map will display both locations

2. **Select Vehicle Type**:
   - Choose from available vehicle options
   - View estimated fare

3. **Find Trip**:
   - Click "Find Trip" to send request
   - Wait for captain acceptance

4. **Trip Start**:
   - Captain arrives at pickup location
   - Share the OTP with captain
   - Captain verifies OTP to start trip

5. **During Trip**:
   - Both user and captain can track journey progress
   - Real-time location updates on map
   - Estimated time of arrival displayed

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


