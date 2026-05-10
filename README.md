# Programming Joke Generator

A simple React application that fetches and displays random programming jokes using the JokeAPI.

## Features
Fetches a programming joke when the application loads
Allows users to fetch a new joke with a button click
Displays a loading message while fetching data
Uses useEffect for handling side effects
Uses useState for state management

## Technologies Used
React
Vite
JavaScript
JokeAPI

## API Used

The application fetches jokes from:

https://v2.jokeapi.dev/joke/Programming?type=single

## Project Structure
src/
│
├── App.jsx
├── main.jsx
└── __tests__/
    └── App.test.jsx

## Installation
1. Clone the repository
git clone <repository-url>

2. Navigate into the project folder
cd <project-folder>

3. Install dependencies
npm install

4. Start the development server
npm run dev

### Running Tests

*** Run the test suite using: ***

npm test

or

npx vitest

### How It Works
When the application loads, useEffect triggers an API request.
The fetched joke is stored using useState.
Clicking the Get a New Joke button fetches another random joke.
A loading message is displayed while waiting for the API response.

### Example UI
Programming Jokes

Why do programmers prefer dark mode?

[ Get a New Joke ]

### Author

Ruth Wanja Juma
