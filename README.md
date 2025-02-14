# Express.js Route Parameter Handling Error
This repository demonstrates a common error in Express.js route parameter handling and its solution.  The bug involves failing to handle cases where a requested resource (e.g., a user) is not found.

## Bug Description
The code attempts to fetch user details based on a provided ID. If no user with that ID exists, it doesn't gracefully handle the situation, leading to unexpected behavior or errors.

## Solution
The solution includes robust error handling to check if a user is found.  If not, it returns an appropriate 404 Not Found response.