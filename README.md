[![License: Unlicense](https://img.shields.io/badge/License-Unlicense-blue.svg)](https://opensource.org/licenses/Unlicense)

# Note Taking App

A simple web application that allows users to create and delete notes. Built with HTML, CSS, and JavaScript, and powered by Express and Node.js. Notes are assigned unique IDs using the `uuid` package and are stored in a JSON file as the database.

## Features

- Create new notes with a title and content.
- Delete existing notes.
- Unique IDs for notes using the `uuid` package.
- Data persistence using a JSON file as the database.

## Prerequisites

- [Node.js](https://nodejs.org/)
- [npm](https://www.npmjs.com/)

## Getting Started

1. Clone the repository:

   ```bash
   git clone https://github.com/your-username/note-taking-app.git
   cd note-taking-app

   ```

2. Install the dependencies

   `npm install`

3. Start the server

   `npm start`

4. Open your browser and navigate to `http://localhost:3000` to access the app.

## Deployment to Heroku

1. Make sure you have the [Heroku CLI](https://devcenter.heroku.com/articles/heroku-cli) installed.

2. Login to Heroku:

   ```bash
   heroku login

   ```

3. Open the app in your browser:
   ```bash
   heroku open
   ```
