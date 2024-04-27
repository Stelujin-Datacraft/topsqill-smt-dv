```markdown
# TopSqill SMT Development Repository

Welcome to the TopSqill SMT development repository! This repository houses the source code for both the frontend and backend components of the TopSqill SMT (No Code Solution and Management Tool). The project is aimed at developing a user-friendly, no-code platform to streamline workflows, create and manage project data, and improve operational efficiency.

## Technologies Used

### Frontend
- Framework: React.js
- UI Design: Material-UI
- State Management: Redux
- Package Manager: npm

### Backend
- Framework: Node.js (Express.js)
- Database: MongoDB
- Authentication: JSON Web Tokens (JWT)
- Cloud Deployment: AWS (Amazon Web Services)
- Containerization: Docker

## Folder Structure

```
topsqill-smt/
│
├── frontend/               # Frontend codebase
│   ├── src/                # Source code directory
│   │   ├── components/     # Reusable UI components
│   │   ├── pages/          # Individual pages or screens
│   │   ├── store/          # Redux store setup and actions
│   │   ├── utils/          # Utility functions
│   │   └── App.js          # Main application component
│   ├── public/             # Public assets
│   └── package.json        # Frontend dependencies and scripts
│
├── backend/                # Backend codebase
│   ├── src/                # Source code directory
│   │   ├── controllers/    # Request handlers
│   │   ├── models/         # Data models
│   │   ├── routes/         # API routes
│   │   ├── config/         # Configuration files (e.g., database connection)
│   │   ├── middleware/     # Custom middleware
│   │   ├── services/       # Business logic and utility services
│   │   └── app.js          # Express application setup
│   ├── Dockerfile          # Docker configuration for containerization
│   └── package.json        # Backend dependencies and scripts
│
└── README.md               # You are here!
```

## Getting Started

To get started with the development environment, follow these steps:

1. Clone this repository to your local machine.
2. Navigate to the `frontend` directory and install dependencies:
   ```
   cd frontend/
   npm install
   ```
3. Navigate to the `backend` directory and install dependencies:
   ```
   cd ../backend/
   npm install
   ```
4. Set up environment variables:
   - Create a `.env` file in the `backend` directory and define environment variables such as MongoDB connection URI, JWT secret, etc.
5. Run the frontend and backend servers:
   - For frontend: `npm start` in the `frontend` directory.
   - For backend: `npm start` in the `backend` directory.

## Contribution Guidelines

- Fork the repository and create a new branch for your feature or bug fix.
- Make your changes and ensure they follow the coding standards.
- Write tests for your code if applicable.
- Commit your changes and submit a pull request to the `dev` branch of this repository.

## Contact Information

For any questions or assistance, feel free to reach out to the development team:

- Project Manager: Stelujin Georgekutty Nedungottu
  - Email: stelujin.george@gmail.com
- Frontend Lead: Sarvesh Kadwade
  - Email: [sarvesh.kadwade@gmail.com]
- Backend Lead: Utkarsh Kulkarni
  - Email: [ukulkarni13@example.com]
```
