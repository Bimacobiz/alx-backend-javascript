# 0x06-unittests_in_js

## Overview
This project is aimed at learning unit testing in JavaScript using popular testing frameworks such as Mocha, Chai, and Sinon. It covers various aspects of writing and running unit tests for JavaScript code to ensure its correctness and reliability.

## Learning Objectives
Upon completing this project, you should be able to explain the following concepts without needing external resources:
- Using Mocha to write test suites
- Utilizing different assertion libraries like Chai or Node's assert module
- Organizing and presenting lengthy test suites
- Understanding and implementing spies and stubs
- Working with hooks and knowing when to use them
- Testing async functions
- Writing integration tests with a small Node.js server

## Requirements
- All code will be executed on Ubuntu 18.04 using Node 12.x.x
- Allowed editors: vi, vim, emacs, Visual Studio Code
- All files should end with a new line
- A README.md file at the root of the project folder is mandatory
- Code files should use the .js extension
- When running tests with `npm run test *.test.js`, all tests should pass without errors or warnings

## Resources
Before starting the tasks, it's recommended to read or watch the following resources:
- [Mocha documentation](https://mochajs.org/)
- [Chai](https://www.chaijs.com/)
- [Sinon](https://sinonjs.org/)
- [Express](https://expressjs.com/)
- [Request](https://github.com/request/request)
- [How to Test NodeJS Apps using Mocha, Chai, and SinonJS](https://dev.to/jploskonka/how-to-test-nodejs-apps-using-mocha-chai-and-sinonjs-47na)

## Tasks
### 0. Basic test with Mocha and Node assertion library
- Install Mocha using npm
- Set up npm scripts to run Mocha tests
- Write a function `calculateNumber` in 0-calcul.js and corresponding tests in 0-calcul.test.js

### 1. Combining descriptions
- Upgrade the `calculateNumber` function to support different operations (SUM, SUBTRACT, DIVIDE)
- Write tests for the updated function in 1-calcul.test.js

### 2. Basic test using Chai assertion library
- Rewrite the tests for `calculateNumber` using Chai's `expect` syntax
- Copy existing files to 2-calcul_chai.js and 2-calcul_chai.test.js

### 3. Spies
- Create a function in utils.js and a corresponding test in 3-payment.test.js using Sinon's spies

### 4. Stubs
- Stub the function in 4-payment.js using Sinon
- Write tests in 4-payment.test.js to verify the stub's behavior

### 5. Hooks
- Use beforeEach and afterEach hooks to write tests in 5-payment.test.js
- Ensure console.log is called only once for each test case

### 6. Async tests with done
- Write async tests in 6-payment_token.test.js using Mocha's `done` callback

### 7. Skip
- Skip failing tests in 7-skip.test.js without fixing them
- Ensure all other tests pass without issues

### 8. Basic Integration testing
- Create an Express server in 8-api/api.js
- Write integration tests in 8-api/api.test.js to verify server responses

### 9. Regex integration testing
- Modify the Express server to support regex-based routes
- Write integration tests in 9-api/api.test.js to validate route behavior

### 10. Deep equality & Post integration testing
- Expand the Express server to include additional endpoints
- Write integration tests in 10-api/api.test.js to test the new functionality


