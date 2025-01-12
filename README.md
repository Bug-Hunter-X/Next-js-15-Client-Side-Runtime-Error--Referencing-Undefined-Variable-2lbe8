# Next.js 15 Client-Side Runtime Error: Referencing Undefined Variable

This repository demonstrates a runtime error in a Next.js 15 application that occurs only on the client-side when navigating to a specific page. The error is caused by referencing an undefined variable within a component.

## Bug Description
The `about.js` file contains a component that references a variable (`nonExistentVariable`) which is not defined, leading to a runtime error on the client-side. This issue highlights the importance of proper variable handling in Next.js applications.

## How to Reproduce
1. Clone this repository.
2. Run `npm install` to install dependencies.
3. Run `npm run dev` to start the development server.
4. Navigate to the `/about` page.  The error will appear in the browser console.

## Solution
The solution involves defining the variable that was causing the error. The `aboutSolution.js` demonstrates this fix.