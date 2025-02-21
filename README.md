# React useEffect Cleanup Function Issue

This repository demonstrates a problem with the cleanup function in React's `useEffect` hook.  The cleanup function is intended to run when the component unmounts or when the effect's dependencies change, allowing for resource cleanup (e.g., cancelling network requests, clearing timers).

In this example, the cleanup function isn't always triggered, which could lead to unexpected behavior and resource leaks. The `bug.js` file showcases the problem; the solution is in `bugSolution.js`.