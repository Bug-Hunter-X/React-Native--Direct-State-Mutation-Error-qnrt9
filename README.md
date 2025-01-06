# React Native Direct State Mutation Error
This repository demonstrates a common error in React Native functional components: directly mutating the state variable instead of using the setter function provided by `useState`.  The `bug.js` file contains the erroneous code. The solution is presented in `bugSolution.js`.

## How to reproduce the error
Clone this repository, navigate to the directory in your terminal, and run the following command:
```bash
npm install
npm start
```
Observe the incorrect behavior in `bug.js` where clicking the button will not update the counter.  Then compare it with the corrected code in `bugSolution.js`.