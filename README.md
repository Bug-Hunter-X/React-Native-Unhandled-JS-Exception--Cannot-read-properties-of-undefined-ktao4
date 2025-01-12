# React Native Unhandled JS Exception: Cannot read properties of undefined

This repository demonstrates a common error in React Native applications: the "Cannot read properties of undefined (reading '...')" exception.  This typically occurs when accessing a state variable or prop before it's been properly initialized.

The `bug.js` file showcases the problematic code, while `bugSolution.js` provides a corrected version.  The error arises from attempting to access a property of a state variable before the state has been properly set, leading to the runtime error.  The solution involves using conditional rendering or the optional chaining operator to handle cases where the state variable might be undefined.

## How to Reproduce

1. Clone this repository.
2. Navigate to the project directory.
3. Run `npm install` or `yarn install` to install dependencies.
4. Run the app using the appropriate React Native command (e.g., `npx react-native run-android` or `npx react-native run-ios`).
5. Observe the error in the console.  Compare the error with the solutions provided.

## Solutions

The solution involves checking if the state variable is defined before accessing its properties.