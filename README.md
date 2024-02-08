# Browser-Text-Editor
## Table of Contents
- [Title](#title)
- [Description](#description)
- [Installation](#installation)
- [Usage](#usage)
- [License](#license)
- [Screenshots](#screenshots)
## Description
This repository contains the source code for a web service "(not) Just Another Text Editor." This project is fully deployed and can be used in the browser to quickly create JavaScript code segments that immediately get stored in IndexedDB, and local storage as a fallback. These segments are updated with every change on the document, and when the user clicks away unfocusing the window. Because this is a PWA (Progressive Web App), most of its assets are precached in the browser through a web service worker, making it very performant. It is also fully installable! 
## Installation
To visit and use the live site immediately, simply click on the link to the project in 'Usage.' Otherwise, if you'd like to run this application locally you can follow these steps:

  1. Clone the project
  2. In the root directory of the project, run the script:
  3. `npm run install` to download all dependencies in the server and client, then:
  4. `npm run start` to build the app with Webpack, and start the server simultaneously
  5. You should be set to go to localhost:3000 and immediately try it out!
  6. Don't forget to close the server once you're done running it locally with 'Ctrl + C'
  
## Usage

Link to project: https://just-another-text-editor-tq3x.onrender.com

Once the application is opened you'll be greeted with the editor, containing line numbers along the left side that we all love to see. Every time the editor is completely empty and you refresh the page, you'll be greeted with the "JATE" ascii art. To download the page and easily create a desktop shortcut on your machine, just press the 'Install' button and accept the window prompt. Any changes you make on the external app will be reflected in your browser, how cool!
## License
ISC
## Screenshots
<img width="500" alt="Screenshot 2024-02-07 183848" src="https://github.com/JBassard97/Browser-Text-Editor/assets/142551579/d328a268-15c8-48fd-9c54-9c2300158928">

<img width="500" alt="Screenshot 2024-02-07 183641" src="https://github.com/JBassard97/Browser-Text-Editor/assets/142551579/f37cde32-f248-4cd4-a58c-79c0d2e148e9">

<img width="500" alt="Screenshot 2024-02-07 184149" src="https://github.com/JBassard97/Browser-Text-Editor/assets/142551579/5428d91b-ea8b-4fca-b2e4-d8722b2cf508">

<img width="500" alt="Screenshot 2024-02-07 184629" src="https://github.com/JBassard97/Browser-Text-Editor/assets/142551579/29ec254d-b505-4d07-887f-6f54bf177aa6">

