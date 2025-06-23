# Task Manager Fullstack Application

This project is a full-stack task manager application with a React frontend and a Node.js/Express backend API.

## Tech Stack

- Frontend: React 19, Axios, Jest, React Testing Library, Babel, React Scripts
- Backend: Node.js, Express, MongoDB, Mongoose, Jest

## API

The backend API provides CRUD operations for managing tasks.

## Running the Application

### Backend

1. Navigate to the backend directory:
```
cd task-manager-api/server
```
2. Start the backend server:
```
node server.js
```

### Frontend

1. Navigate to the frontend directory:
```
cd task-manager-api-client
```
2. Start the frontend development server:
```
npm start
```
3. Open [http://localhost:3000](http://localhost:3000) in your browser.

## Testing

### Frontend Tests

- Jest and React Testing Library are used for unit testing React components.
- Axios is mocked in tests to simulate API calls.
- Run frontend tests with coverage:
```
npm test -- --coverage --watchAll=false
```
- Coverage report is generated in the `coverage` directory.

### Backend Tests

- Jest is used for unit, integration, and API endpoint testing.
- Tests cover CRUD operations and model validations.
- Run backend tests with coverage:
```
npm test -- --coverage --watchAll=false
```
- Coverage report is generated in the `coverage` directory inside the backend folder.

## Test Coverage



### Frontend Coverage

![Frontend Test Coverage]

### Backend Coverage

![Backend Test Coverage]

*Please replace the above paths with the actual screenshots of your test coverage.*

## Additional Information

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

For more information, see the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).
