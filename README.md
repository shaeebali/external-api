# External API Application

This project demonstrates how to consume external APIs within a Node.js and Express backend, and display the data on a frontend built with React.js and Redux Toolkit for state management.

## Features

- **API Consumption**: Fetches data from external APIs and displays it dynamically on the frontend.
- **React Frontend**: Built using React.js, leveraging JSX syntax for creating reusable components.
- **State Management**: Utilizes Redux Toolkit for managing global state efficiently.
- **Asynchronous Requests**: Uses async/await for API data fetching.
- **Modular Structure**: Clean separation between backend and frontend code.

## Tech Stack

- **Backend**: Node.js, Express
- **Frontend**: React.js, Redux Toolkit
- **External APIs**: Integration with third-party APIs (specify which APIs)

## Vanilla JavaScript vs. React (JSX)

- **Vanilla JavaScript**: Involves manipulating the DOM directly and manually managing UI updates.
- **React (JSX)**: Utilizes a component-based architecture, enabling reusable code and faster development. JSX (JavaScript XML) allows you to write HTML-like syntax within JavaScript, making UI creation more declarative. React also optimizes DOM updates via its Virtual DOM, improving performance.

## Getting Started

### 1. Clone the repository
```bash
git clone https://github.com/shaeebali/external-api.git
cd external-api
```

### 2. Install dependencies
For the backend:
```bash
cd backend
npm install
npm start
```

For the frontend:
```bash
cd frontend
npm install
npm start
```

### 3. Access the Application
- **Backend**: The server runs at `http://localhost:5000`.
- **Frontend**: Access the React app at `http://localhost:3000`.

## Project Structure

```
- backend/   # Node.js and Express logic
- frontend/  # React.js and Redux Toolkit files
- .env       # Environment variables for API keys
```

## API Keys and Environment Variables

Set your API keys in the `.env` file:
```bash
API_KEY=<your_api_key>
```

## License

This project is licensed under the MIT License.
