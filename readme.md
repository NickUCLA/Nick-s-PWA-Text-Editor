# Progressive Web Application Text Editor

## Table of Contents

1. [Description](#description)
2. [Technology](#technology)
3. [Installation](#installation)
4. [Visuals](#visuals)
5. [License](#license)

## Description

The Progressive Web Application Text Editor is a versatile web app that seamlessly operates in both online and offline modes. It is designed to provide users with a reliable platform for taking notes or writing code snippets, regardless of their internet connection status.

The application can also be used as a freestanding tool, thanks to its integrated service worker and Cache APIs. It's perfect for users who need a flexible text editor that adapts to their connectivity needs.

[Access the deployed app on Heroku]()

## Technology

This application leverages a stack of modern technologies to deliver a robust user experience. The key technologies used include:

- Express: For the server-side framework.
- IndexedDB: To manage client-side storage.
- Webpack & WebpackPwaManifest Plugins: For efficient bundling and creating progressive web app manifests.
- Concurrently: To run multiple processes concurrently.
- Babel: For JavaScript transpilation.
- Heroku: To host the live application.

## Installation

Follow these steps to set up the application on your local machine:

1. Clone this repository to your computer.
2. Open your terminal/command prompt and navigate to the root directory of the project.
3. Run the following command to install the necessary dependencies:
   `npm install`

4. Once the dependencies are installed, start the application by running the following command:
   `npm run start:dev`
