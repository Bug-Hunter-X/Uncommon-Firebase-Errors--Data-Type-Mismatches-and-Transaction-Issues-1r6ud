# Uncommon Firebase Errors
This repository demonstrates two uncommon errors that can occur when using the Firebase SDK: data type mismatches and improper transaction handling.

## Data Type Mismatch
The `firebaseBug.js` file shows an example of attempting to insert an array into a field that expects a map. This can lead to silent data loss or unexpected application behavior.

## Transaction Handling
The `firebaseBug.js` file also includes an example of how improper transaction handling can lead to inconsistent data.

## Solutions
The `firebaseBugSolution.js` file provides corrected versions of the code, addressing the data type mismatch and transaction errors.

## How to Run
1. Ensure you have Node.js and npm installed.
2. Install the Firebase Admin SDK: `npm install firebase-admin`
3. Configure your Firebase project. 
4. Run the example files using Node.js: `node firebaseBug.js` and `node firebaseBugSolution.js`