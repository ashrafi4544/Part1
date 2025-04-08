# Anecdotes Application

This is a simple React application built with Vite that displays random anecdotes and allows users to vote for their favorites. The application shows one anecdote at a time and maintains a vote count for each. It also highlights the anecdote with the highest number of votes.

## Features

- **Random Anecdotes:** Displays a random anecdote from a predefined list.
- **Voting System:** Users can vote for the currently displayed anecdote.
- **Dynamic Statistics:** Shows the number of votes for the selected anecdote and highlights the anecdote with the most votes.
- **Conditional Rendering:** Displays a notification if no votes have been cast.

## Project Structure

anecdotes-application/ ├── node_modules/ # Installed dependencies ├── public/ # Static files (e.g., index.html) ├── src/ │ ├── App.jsx # Main React component containing the application logic │ ├── index.jsx # Application entry point (renders <App />) │ └── ... # Other supporting files (if any) ├── .gitignore # Lists files/folders to be ignored by Git (e.g., node_modules/) ├── package.json # Project dependencies and scripts └── README.md # This file


## Prerequisites

Before running the project, ensure you have the following installed:

- [Node.js](https://nodejs.org/) (LTS version recommended)
- npm or yarn as your package manager

You can check if these are installed by running:

```bash
node -v
npm -v
