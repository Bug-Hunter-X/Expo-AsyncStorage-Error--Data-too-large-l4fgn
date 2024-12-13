# Expo AsyncStorage Error: Data too large

This repository demonstrates a common error encountered when using AsyncStorage in Expo applications: attempting to store large JSON objects exceeding AsyncStorage's size limits. This leads to app crashes or errors.

The `bug.js` file shows the problematic code, and `bugSolution.js` provides a solution using techniques to handle larger datasets efficiently.

## How to Reproduce

1. Clone the repository.
2. Run `npm install` to install dependencies.
3. Run the app in your Expo Go client.
4. Observe the error or unexpected behavior when attempting to store large data.