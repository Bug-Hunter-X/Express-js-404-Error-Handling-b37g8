# Express.js 404 Error Handling

This repository demonstrates a common error in Express.js applications where attempting to serve a file that does not exist leads to a crash.  The solution provides a more robust approach to handle 404 errors gracefully.

## Bug

The `bug.js` file contains an Express.js application that attempts to serve `index.html`. If `index.html` is not found, the application crashes with a 404 error.

## Solution

The `bugSolution.js` file demonstrates a solution that gracefully handles the 404 error. It checks if the file exists before attempting to send it.