# React Router DOM v6 Route Path Issue

This repository demonstrates a subtle bug in React Router DOM v6 where subsequent routes defined in the `Routes` component fail to render, without throwing any errors in the console.  The issue only affects routes after the first one defined.

## How to Reproduce

1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm start` to start the development server.
4. Navigate to `/about` or `/contact`.  You will notice only `/` renders correctly.

## Solution

The solution is provided in `AppSolution.js`, showing a common issue that may resolve this.  Refer to the file and the included explanation for the correction.