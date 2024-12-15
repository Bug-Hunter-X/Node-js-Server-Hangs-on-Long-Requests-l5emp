# Node.js Server Hang Issue

This repository demonstrates a common issue in Node.js where long-running operations in request handlers can block the event loop, causing the server to become unresponsive. The `server.js` file contains the buggy code, while `serverSolution.js` provides a solution using asynchronous operations and promises to avoid blocking the event loop.