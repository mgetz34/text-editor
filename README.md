# Text Editor

## License

![License](https://img.shields.io/badge/license-MIT-green)

## Table of Contents:

- [User Story](#user-story)

- [Acceptance Criteria](#acceptance-criteria)

- [License](#license)

- [Description](#description)

- [Installation](#installation)

- [Usage](#usage)

- [Questions](#questions)

- [Depolyed App](#deployed-app)

## License

This Application is covered by a: ![License](https://img.shields.io/badge/license-MIT-green)

## User Story

```
AS A developer
I WANT to create notes or code snippets with or without an internet connection
SO THAT I can reliably retrieve them for later use
```

## Acceptance Criteria

```
GIVEN a text editor web application
WHEN I open my application in my editor
THEN I should see a client server folder structure
WHEN I run `npm run start` from the root directory
THEN I find that my application should start up the backend and serve the client
WHEN I run the text editor application from my terminal
THEN I find that my JavaScript files have been bundled using webpack
WHEN I run my webpack plugins
THEN I find that I have a generated HTML file, service worker, and a manifest file
WHEN I use next-gen JavaScript in my application
THEN I find that the text editor still functions in the browser without errors
WHEN I open the text editor
THEN I find that IndexedDB has immediately created a database storage
WHEN I enter content and subsequently click off of the DOM window
THEN I find that the content in the text editor has been saved with IndexedDB
WHEN I reopen the text editor after closing it
THEN I find that the content in the text editor has been retrieved from our IndexedDB
WHEN I click on the Install button
THEN I download my web application as an icon on my desktop
WHEN I load my web application
THEN I should have a registered service worker using workbox
WHEN I register a service worker
THEN I should have my static assets pre cached upon loading along with subsequent pages and static assets
WHEN I deploy to Heroku
THEN I should have proper build scripts for a webpack application
```

## Description

The app was build as a text editor that runs in the browser. This app is a single-page application that meets PWA criteria. This app also features a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline.
This app utilizes a package called idb, which is a lightweight wrapper around the IndexedDB API. IDB features a number of methods that are useful for storing and retrieving data. The importance of PWAs is ever increasing in the development community. This application helped to learn the concepts of PWAs and associated criteria, indexdDB use and implementation, and service-worker use for offline app functionality and data-persistance.

## Installation

npm i, npm run start, navigate to http://localhost:3000, use app with or without an internet connection, or download the app for desktop!

## Usage

![home screen](./client/src/images/Screenshot%202023-01-06%20201930.png)

## Questions

For any questions, please view my repo at: https://github.com/mgetz34
My email address is: mgetz340@gmail.com

## Deployed App

https://serene-spire-38646.herokuapp.com/
