# Events Tracker
A web-based event booking management application built with React and Vite. Events Tracker provides a simple interface to create, view, update, and manage event bookings.
## Live Demo
**Frontend:** https://event-selector.web.app/
## Features
- Add new event bookings
- View existing bookings
- Update booking details
- Delete bookings
- Simple and responsive user interface
- Navigation between booking pages
- Backend API integration for booking operations
## Tech Stack
### Frontend
- React
- Vite
- JavaScript
- CSS
### Backend
- Node.js
- Express.js
- REST API
### Deployment
- Firebase Hosting — Frontend
- Render — Backend
## Project Structure
```text
Events-Tracker/
├── public/
│   ├── favicon.svg
│   └── icons.svg
├── src/
│   ├── assets/
│   ├── components/
│   │   └── Navbar.jsx
│   ├── pages/
│   │   ├── AddBooking.jsx
│   │   └── ShowBooking.jsx
│   ├── App.jsx
│   ├── App.css
│   ├── index.css
│   └── main.jsx
├── index.html
├── package.json
├── vite.config.js
└── README.md
```
## Getting Started
### Prerequisites
Make sure you have the following installed:
- [Node.js](https://nodejs.org/)
- npm
### Installation
Clone the repository:
```bash
git clone https://github.com/aradhyasalve18/events-FE.git
```
Navigate to the project directory:
```bash
cd YOUR_PROJECT_NAME
```
Install dependencies:
```bash
npm install
```
Start the development server:
```bash
npm run dev
```
Open the local URL displayed in your terminal, usually:
```text
http://localhost:5173
```
## Available Scripts
| Command | Description |
|---|---|
| `npm run dev` | Start the development server |
| `npm run build` | Build the application for production |
| `npm run preview` | Preview the production build locally |
| `npm run lint` | Run ESLint |
## Backend
The backend is maintained in a separate repository and deployed independently.
The frontend communicates with the backend through HTTP API requests to perform booking operations.
## Deployment
The frontend is deployed using Firebase Hosting.
To create a production build:
```bash
npm run build
```
The generated production files are available in the `dist/` directory.
Fr. Conceicao Rodrigues College of Engineering

