React Pagination
A simple React application demonstrating pagination using react-paginate. The project fetches posts from a placeholder API and displays them with pagination.

Features
Fetches data from the JSONPlaceholder API.
Displays posts in a paginated table.
Fully responsive design using react-bootstrap and bootstrap.
Pagination handled by the react-paginate library.
Loader displayed while data is being fetched.

Technologies Used
React: Component-based UI development.
Bootstrap: Responsive styling.
React-Bootstrap: Prebuilt React components for Bootstrap.
React-Paginate: Pagination component for React.
JSONPlaceholder API: Free fake API for testing and prototyping.

Prerequisites
Node.js: Ensure you have Node.js installed. Download Node.js.

Getting Started
Clone the Repository:
bash
Copy code
git clone https://github.com/yourusername/react-pagination.git
cd react-pagination
Install Dependencies:

bash
Copy code
npm install
Run the Application:

bash
Copy code
npm run dev
Open your browser and visit: http://localhost:5173.

Scripts
npm run dev: Start the development server.
npm run build: Build the app for production.
npm run preview: Preview the production build.
npm run lint: Run ESLint for code quality checks.

How to Use
Start the app by running the development server.
The application fetches posts data and displays them in a paginated table.
Use the pagination controls at the bottom of the table to navigate between pages.

Dependencies
react: UI framework.
react-dom: Rendering React components.
react-bootstrap: Bootstrap components for React.
bootstrap: CSS framework for styling.
react-paginate: Pagination handling.
Dev Dependencies
vite: Build tool.
eslint: JavaScript and React linting.
@vitejs/plugin-react: Vite plugin for React support.
@types/react & @types/react-dom: TypeScript typings for React and React DOM.
API Reference
The app fetches data from JSONPlaceholder API. Each post includes:

id: Unique post ID.
title: Post title.
body: Post content.

Author
Asad

If you encounter any issues or have suggestions for improvement, feel free to reach out or create an issue. 😊

