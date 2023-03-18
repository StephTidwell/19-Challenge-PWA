# 19-challenge-PWA: Text Editor


## Description
This is a browser-based text editor. The app will be a single-page app that fulfills the PWA requirements. It will also provide a variety of data persistence strategies as redundancy in case one of the choices is not supported by the browser. The app will also work while you are not connected to the internet.


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
## Table of Contents

- [Application Preview](#application-preview)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies](#technologies)
- [License](#license)

### Application Preview

[Deployed Link](https://guarded-cliffs-83260.herokuapp.com/)

```

<img width="1680" alt="Screen Shot_challenge_19_PWA" src="https://user-images.githubusercontent.com/113862737/226134951-a6ced9d7-cf8e-49e0-84de-48f1ddd1651b.png">
```


### Installation
Download or clone this repository to use this code on your local system. After installing the required dependencies, browse to the root directory and execute the following command:
```
npm i 
```
### Usage

- Open the terminal in the root folder to run this application:
```
npm start
```
- When you run the command, the server will be launched; navigate to the application's URL.
- Type any text into the editor. Your text will then be saved automatically when you click off of the window. 
You can install this PWA on your devices for offline usage.

### Technologies

- Express.js
- IndexedDB
- Node.js
- PWA
- Heroku

### License 
This project is covered under the MIT license. To learn more about what this means, click the license button below.
![MIT license](https://img.shields.io/badge/License-MIT-blue.svg)
* Github: https://github.com/StephTidwell
