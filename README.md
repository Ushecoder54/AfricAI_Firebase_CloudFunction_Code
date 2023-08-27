# Quiz App Firebase Cloud Functions

This repository contains the TypeScript code for Firebase Cloud Functions that power the backend of a quiz app.

## Features

- Randomly selects questions from a Firestore database.
- Checks user-submitted answers and provides feedback.
- Integrates user authentication, timer, retry functionality, and more.
- Supports progress indication, correct/wrong answer explanations, and more.

## Getting Started

1. Clone this repository to your local machine.
2. Set up your Firebase project and configure Firebase CLI.
3. Install the necessary dependencies using `npm install`.

## Usage

1. Edit the `quiz_functions.ts` file to customize your quiz app's functionality.
2. Deploy the Firebase Cloud Functions using `firebase deploy --only functions`.

## Structure

- `quiz_functions.ts`: Main TypeScript file containing Firebase Cloud Functions code.
- `package.json`: Project configuration and dependencies.

## Configuration

Before deploying the functions, make sure to configure your Firebase project by running:

```shell
firebase login
firebase use --add

Dependencies
The project uses the following dependencies:

firebase-admin: Firebase Admin SDK for server-side functionality.
firebase-functions: Firebase Functions SDK for building Cloud Functions.
License
This project is licensed under the MIT License.

```
