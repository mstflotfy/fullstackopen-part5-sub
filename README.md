Full Stack Open - Part 5 Submission
This repository contains the code for the exercises in Part 5 of the Full Stack Open course. It includes the following components:

    Frontend (React)
    Backend (Express)
    E2E tests (Playwright)

Project Structure
The project is organized into the following subfolders:

    frontend: Contains the React-based frontend application.
    backend: Contains the backend application, built with Node.js and Express.
    tests: Contains the Playwright-based end-to-end tests.

Getting Started
To run the project locally, follow these steps:
1. Clone the repository

bash
git clone https://github.com/mstflotfy/fullstackopen-part5-submission
cd fullstackopen-part5-submiss

2. Install dependencies
Navigate to each subfolder and install the dependencies:

bash
# Frontend
cd frontend
npm install

# Backend
cd ../backend
npm install

# Tests
cd ../playwrigh-tests
npm install

3. Start the applications
In separate terminal windows, start the frontend, backend, and run the tests:

bash
# Frontend
cd frontend
npm run dev

# Backend
cd ../backend
npm run start:test

# Tests
cd ../playwrigh-tests
npm run test -- --ui

The frontend will be available at http://localhost:3003, the backend at http://localhost:3001, and the Playwright tests will run in playwright ui.
Submission Details


