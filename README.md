# Doctor Booking Application

A web-based application to enable users to book appointments with doctors.

---

## Features

- User authentication (Login/Signup).
- Searchable Doctor directory.
- Appointment scheduling.
- MongoDB for data storage.

---

## Prerequisites

Ensure you have the following installed:

- **Node.js** (v18.16.1 or higher)
- **MongoDB** (local or Atlas connection)
- **npm** (Node Package Manager)

---

## Setup Instructions

### 1. Clone the repository

```bash
git clone https://github.com/your-username/doctor-booking-application.git
```

### 2. Navigate to the project directory

```bash
cd doctor-booking-application
```

### 3. Install Backend dependencies

```bash
cd backend
npm install
```

### 4. Install Frontend dependencies

```bash
cd ../frontend
npm install
```

---


## Running the Application

### 1. Start the Backend server

```bash
cd backend
npm run dev
```

### 2. Start the Frontend server

```bash
cd ../frontend
npm start
```

---

## Project Structure

```plaintext
doctor-booking-application/
├── backend/
│   ├── config/          # Configuration files (e.g., database connection)
│   ├── controllers/     # Backend logic for routes
│   ├── models/          # Database models (e.g., User, Appointment)
│   ├── routes/          # API routes
│   ├── .env             # Environment variables
│   ├── index.js         # Backend entry point
├── frontend/
│   ├── public/          # Static files
│   ├── src/             # React components and logic
│   ├── package.json     # Frontend dependencies
├── README.md            # Project documentation
```

---

## Available Scripts

### Backend
- **Start Development Server**:

```bash
npm run dev
```

- **Start Production Server**:

```bash
npm start
```

### Frontend
- **Start React Application**:

```bash
npm start
```

- **Build for Production**:

```bash
npm run build
```

---

## Troubleshooting

- If the backend fails to start, check the `.env` file for valid MongoDB URI and JWT secret.
- Ensure that your MongoDB is running, or the Atlas URI is correct.
- For frontend issues, check the browser's console for errors.
