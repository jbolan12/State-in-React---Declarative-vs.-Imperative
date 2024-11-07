# State-in-React---Declarative-vs.-Imperative

# Toggle Strike Through

A simple React app that demonstrates toggling the text decoration (line-through) on a paragraph based on user interaction. This app allows the user to strike through the text by clicking a button and then remove the strike-through with another button.

## Table of Contents

1. [Overview](#overview)
2. [Installation](#installation)
3. [Usage](#usage)
4. [Technologies](#technologies)
5. [Scripts](#scripts)
6. [License](#license)

## Overview

This app includes:
- A paragraph with the text "Buy milk."
- Two buttons: one to apply a "strike-through" text decoration and another to remove it.

When the first button is clicked, the text decoration is set to `line-through`. When the second button is clicked, the text decoration is removed.

## Installation

### Prerequisites

- Node.js (version 14 or above)
- npm (version 6 or above)

### Steps

1. Clone the repository:

   ```bash
   git clone https://github.com/jbolan12/State-in-React---Declarative-vs.-Imperative.git

   Navigate to the project directory:

bash
cd your-repo

**Install the dependencies:**

bash
npm install

**Start the development server:**

bash
npm start
Open http://localhost:3000 in your browser to view the app.

## Usage
The app has the following functionality:

- Strike Button: When the "Change to strike through" button is clicked, the paragraph text changes to have a line-through style.
- Unstrike Button: When the "Change back" button is clicked, the line-through style is removed, returning the text to its original state.
- The app uses inline styles in React to manage the text decoration dynamically.

## Features
- Toggling text decoration: Using line-through and none values for text-decoration based on user interaction.
- Simple UI: A minimalist approach with just a paragraph and two buttons.


## Technologies
- React (v18.3.1)
- React-Dom (v18.3.1)
- React-Scripts (v5.0.1)

## Scripts
- start: Runs the app in development mode with react-scripts start.
- build: Builds the app for production with react-scripts build.
- test: Runs the test suite with react-scripts test --env=jsdom.
- eject: Ejects the app from Create React App configuration.


## License
This project is licensed under the MIT License.
