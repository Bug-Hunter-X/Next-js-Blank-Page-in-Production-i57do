# Next.js Blank Page in Production

This repository demonstrates a common issue in Next.js where an application renders correctly in development but shows a blank page in production. The problem stems from a missing or misconfigured export in the `pages/index.js` file.

## Steps to Reproduce

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm run build` to build the application.
4. Run `npm run start` to start the production server.

Observe that the production server displays a blank page.

## Solution

The solution is to ensure that the `pages/index.js` file correctly exports a React component.