Full Stack Open - Part 5 Submission
This repository contains the code for the exercises in Part 5 of the Full Stack Open course. It uses Git submodules to include the following components:

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
git clone https://github.com/mstflotfy/fullstackopen-part5-sub
cd fullstackopen-part5-sub

2. Intialize submodules:
git submodule update --init --recursive


3. Install dependencies
Navigate to each subfolder and install the dependencies:

bash
# Frontend
cd frontend
npm install

# Backend
cd ../backend
npm install

# Tests
cd ../playwright-tests
npm install

4. Start the applications
In separate terminal windows, start the frontend, backend, and run the tests:

bash
# Frontend
cd frontend
npm run dev

# Backend
cd ../backend
npm run start:test

# Tests
cd ../playwright-tests
npm run test -- --ui

