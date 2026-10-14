# PA3 – Project Management Application

## Assignment Overview
The goal of this assignment was to develop a project management web application using React, Express, and MongoDB.

## What I Implemented
- User signup and login.
- Create projects with a name, description, status, and project lead.
- View project details.
- Automatically add the project lead as a member.
- Add and remove project members.
- Prevent duplicate memberships and prevent removing the project lead.

## Technologies Used
- React
- Node.js and Express
- MongoDB
- JavaScript and CSS

## How to Run

**Backend:**
```bash
cd server
npm install
node server.js
```

**Frontend:** Open a second terminal and run:
```bash
cd client
npm install
npm run dev
```

Configure the required MongoDB connection in `server/.env` before starting the backend.

## Project Structure

```text
icsi418y-pa3/
├── client/
│   ├── public/
│   ├── src/
│   │   ├── assets/
│   │   ├── components/
│   │   │   ├── CreateProject.jsx
│   │   │   ├── Login.jsx
│   │   │   ├── ProjectMemberships.jsx
│   │   │   ├── Projects.jsx
│   │   │   └── Signup.jsx
│   │   ├── App.jsx
│   │   ├── App.css
│   │   └── index.css
│   └── package.json
├── server/
│   ├── server.js
│   └── package.json
├── .gitignore
├── package-lock.json
└── README.md
```

## Database
The application uses the `pa2` database with three collections: `users`, `projects`, and `project_memberships`.

