# 0x05-Node_JS_basic

## Description
This project focuses on learning the basics of Node.js, including running JavaScript with Node.js, using Node.js modules, reading files synchronously and asynchronously, creating HTTP servers using Node.js and Express.js, and organizing a complex HTTP server structure using Express.js.

## Learning Objectives
- Run JavaScript using Node.js
- Use Node.js modules
- Read files using specific Node.js modules
- Access command-line arguments and the environment using the process API
- Create small HTTP servers using Node.js and Express.js
- Create advanced routes with Express.js
- Use ES6 with Node.js with Babel-node
- Use Nodemon for faster development

## Files
- **0-console.js**: Contains a function `displayMessage` that prints a string argument to STDOUT.
- **1-stdin.js**: Prompts the user to input their name, then displays it.
- **2-read_file.js**: Synchronously reads a CSV file and logs the number of students in each field.
- **3-read_file_async.js**: Asynchronously reads a CSV file and logs the number of students in each field.
- **4-http.js**: Creates a simple HTTP server that displays "Hello Holberton School!" for any endpoint.
- **5-http.js**: Creates a more complex HTTP server that displays different messages based on the URL path.
- **6-http_express.js**: Creates a small HTTP server using Express.js that displays "Hello Holberton School!" for the endpoint `/`.
- **7-http_express.js**: Creates a more complex HTTP server using Express.js with different routes and controllers.
- **full_server/**: Directory containing the structure for a full Express.js server.
  - **utils.js**: Contains a function `readDatabase` to read the database asynchronously.
  - **controllers/**: Directory containing controllers for different routes.
    - **AppController.js**: Contains a method `getHomepage` to display the homepage message.
    - **StudentsController.js**: Contains methods to handle student-related routes.
  - **routes/**: Directory containing route handlers.
    - **index.js**: Handles routing for different endpoints.
  - **server.js**: Initializes the Express.js server and defines routes.

## Requirements
- Allowed editors: vi, vim, emacs, Visual Studio Code
- All files interpreted/compiled on Ubuntu 18.04 LTS using node (version 12.x.x)
- All files should end with a new line
- A README.md file at the root of the project directory is mandatory
- Code should use the `.js` extension
- Code will be tested using Jest with the command `npm run test`
- Code will be verified against lint using ESLint with the command `npm run full-test`
- Functions/classes must be exported using `module.exports`

## Installation and Usage
1. Clone the repository:

