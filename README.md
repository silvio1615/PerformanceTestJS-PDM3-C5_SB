# Workspace Reservation System SPA

## Overview

Workspace Reservation System is a Single Page Application (SPA) built with JavaScript, Vite, TailwindCSS, and JSON Server. The application allows users to authenticate, manage workspace reservations, and navigate through protected routes based on their roles.

This project was developed to demonstrate concepts such as:

- SPA Architecture
- Authentication and Authorization
- Role-Based Access Control
- Route Protection
- Session Persistence
- API Consumption
- DOM Manipulation
- Modular JavaScript Development

---

## Features

### Authentication

- User login system
- Session persistence using Local Storage
- Role-based access control

### User Features

- View available reservations
- Create new reservations
- Access personal reservation information

### Administrator Features

- View all reservations
- Approve reservations
- Manage reservation requests
- Access administrative modules

### SPA Navigation

- Dynamic routing without page reloads
- Protected routes
- Custom 404 page

---

## Technologies Used

- JavaScript (ES6+)
- Vite
- TailwindCSS
- JSON Server
- HTML5
- CSS3
- Concurrently

---

## Project Structure

```text
src
├── api
│   └── http.js
├── assets
├── components
│   ├── ReservationCard.js
│   └── Sidebar.js
├── controllers
│   ├── home.controller.js
│   └── login.controller.js
├── router
│   └── router.js
├── services
│   └── reservation.service.js
├── views
│   ├── adminView.js
│   ├── createReservationView.js
│   ├── homeView.js
│   ├── loginView.js
│   └── notFound.js
├── utils.js
├── main.js
└── style.css
```

---

## Installation

Clone the repository:

```bash
git clone <repository-url>
```

Navigate to the project folder:

```bash
cd PerformanceTestJS-PDM3-C5
```

Install dependencies:

```bash
npm install
```

---

## Running the Application

Start the development environment:

```bash
npm run dev
```

This command launches:

- Vite Development Server
- JSON Server API on port 3001

---

## API Configuration

The project uses JSON Server as a mock REST API.

Database file:

```text
db.json
```

API URL:

```text
http://localhost:3001
```

---

## Test Credentials

### Administrator

```text
Email: admin@test.com
Password: A123456
```

### User

```text
Email: user@test.com
Password: A123456
```

### User 2

```text
Email: user2@test.com
Password: A123456
```

---

## Reservation Model

Example reservation object:

```json
{
  "id": "1",
  "userId": "2",
  "workspace": "Sala A",
  "date": "2026-01-15",
  "startHour": "08:00",
  "endHour": "09:00",
  "reason": "Sprint Planning",
  "status": "approved"
}
```

---

## Available Scripts

### Development Mode

```bash
npm run dev
```

### Build Production Version

```bash
npm run build
```

### Preview Production Build

```bash
npm run preview
```

---

## Learning Objectives

This project demonstrates:

- Client-side routing
- Authentication workflows
- Role management
- REST API consumption
- Modular architecture
- Dynamic rendering
- State persistence with Local Storage

---

## Author

Developed by Daniel Álvarez as part of a JavaScript performance assessment project.
