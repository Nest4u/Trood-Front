# Project Management App

This is a simple React application for managing projects. Users can create, edit, delete, and view projects. The app also categorizes projects based on their deadlines.

## Tech Stack
- **Frontend:** React, TypeScript, TailwindCSS
- **Routing:** react-router-dom
- **Backend:** REST API (backend setup is required)

## Features
- Create, edit, and delete projects.
- Categorize projects as active or overdue.
- Navigate between sections using a sidebar.

## How to Run

### Prerequisites
- Install [Node.js](https://nodejs.org/) (14.x or later).
- Ensure you have npm or yarn installed.

### Steps
1. Clone the repository:
   ```bash
   git clone https://github.com/your-repo/project-management-app.git
   cd project-management-app
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Configure the `.env` file:
   - Create a `.env` file in the root directory.
   - Add the backend URL:
     ```env
     REACT_APP_API_URL=http://localhost:8080
     ```

4. Start the application:
   ```bash
   npm start
   ```

5. Open the app in your browser at:
   ```
   http://localhost:3000
   ```

### Backend
- Set up the backend and ensure it matches the `REACT_APP_API_URL` in `.env`. 

