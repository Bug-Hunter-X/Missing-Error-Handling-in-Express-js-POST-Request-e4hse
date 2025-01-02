# Missing Error Handling in Express.js POST Request

This repository demonstrates a common error in Express.js applications: missing error handling for invalid or missing data in POST requests.  The provided `bug.js` file shows an example of a vulnerable endpoint. The `bugSolution.js` file provides a corrected version with robust error handling.

## Bug Description
The `bug.js` file showcases an Express.js application that handles POST requests to `/users`.  It lacks validation and error handling for missing or malformed user data. This can lead to unexpected behavior or application crashes.

## Solution
The `bugSolution.js` file demonstrates how to properly handle these situations. It includes input validation and sends appropriate error responses if the data is invalid or missing.