# Silent Navigation Failure in React Router v6

This repository demonstrates a common issue in React Router v6: silent navigation failures when using `useNavigate` to navigate to non-existent routes.  The issue is that there is no default error handling provided for such scenarios.

The `bug.js` file shows the problem. The `bugSolution.js` file provides a solution.

## How to Reproduce

1. Clone this repository.
2. Run `npm install`
3. Run `npm start`
4. Click the button.  Observe that nothing happens, despite the attempt to navigate to an invalid route.