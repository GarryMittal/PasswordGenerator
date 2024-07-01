# Password Generator Web App

A simple password generator web application built with React. It allows users to generate a random password with customizable length, and options to include numbers and special characters.

## Features

- Generate random passwords
- Customizable length
- Option to include numbers
- Option to include special characters
- Copy to clipboard

## Code Overview

## Components

- **App**: The main component containing the password generator logic and UI.

## State

- **length**: State to store the length of the password.
- **numberAllowed**: State to indicate whether numbers are allowed in the password.
- **charAllowed**: State to indicate whether special characters are allowed in the password.
- **password**: State to store the generated password.

## Functions

- **passwordGenerator**: Generates a random password based on the selected options.
- **copyPassword**: Copies the generated password to the clipboard.

## Hooks

- **useState**: Manages state within the component.
- **useCallback**: Memoizes the password generator and copy functions.
- **useEffect**: Calls the password generator function whenever the dependencies change.
- **useRef**: Creates a reference to the password input field.
