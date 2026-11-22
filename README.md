# School Trip Management System

A web-based system for managing annual school trips, providing tools for student and teacher registration, access control, and real-time participant location tracking.

## Features

- Student and teacher registration.
- Login using a national ID number.
- Teacher authentication using an access code.
- Teacher-only API endpoints and data access.
- Real-time location updates (simulated).
- Live map displaying the locations of all trip participants.

## Design Assumptions

- **Passwordless login:** National ID numbers are used for login to simplify the sign-in process and avoid requiring users to enter a password each time.
- **Role-based access:** Teachers have additional permissions and access to protected information through a dedicated access code.

---

## Technologies Used

### Client (React)
- React
- React Router DOM
- Leaflet (interactive maps)
- Fetch API

### Server (Node.js)
- Node.js
- Express.js
- CORS
- MySQL

### Database
- MySQL
- MySQL2

---

## Running the Project

### Step 1 – Start the Server

```bash
cd server
npm install
npm run dev
```

### Step 2 – Start the Client

Open a separate terminal:

```bash
cd client
npm install
npm run dev
```

Once both services are running, open the local URL provided by Vite in your browser.
