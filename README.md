# React useEffect Hook Missing Cleanup Function
This repository demonstrates a common error in React applications: forgetting to include a cleanup function in the `useEffect` hook.  This can lead to memory leaks or unexpected behavior when the component unmounts.

## The Bug
The `bug.js` file contains a `MyComponent` that updates the document title whenever the `count` state changes.  However, it lacks a cleanup function to reset the title when the component is unmounted.

## The Solution
The `bugSolution.js` file demonstrates the correct usage of the `useEffect` hook with a cleanup function.  This ensures that the title is correctly reset when the component is unmounted, preventing potential issues.

## How to reproduce
1. Clone this repository
2. Navigate to the directory
3. Run `npm install`
4. Run `npm start`
5. Observe the browser tab title