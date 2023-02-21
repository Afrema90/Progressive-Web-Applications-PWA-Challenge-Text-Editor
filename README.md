# Progressive-Web-Applications-PWA-Challenge-Text-Editor
In this Assignment we where asked to build a text editor that runs in the browser. The app will be a single-page application that meets the PWA criteria. Additionally, it will feature a number of data persistence techniques that serve as redundancy in case one of the options is not supported by the browser. The application will also function offline.Installation
This text editor require the Node.js and npm packages. The node package manger also known as the NPM is the software manager and installer which puts the modules in place so that the node can utilize it, and also manages dependency conflicts intelligently and initialized using npm init. The package.json will be generated and will contains all the details of the application in which the user have inputted during the npm initialization.

This application will use the following npm packages:-

  * npm install 
  * npm npm install idb (IndexedDB)
  * Application must have a generated manifest.json using the WebpackPwaManifest plug-in
  * npm run start

The required modules are bundled in the package.json file and at CLI or integrated terminal type in npm run install, the modules will be installed.

Usage
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

this challange was done with the help of my toutor Chris B, study partner David, and the slack ABC

this is the link to the Mock-up https://drive.google.com/file/d/1wbPrCIb3ZFMhac-sMUlMbbDfE9RQzLUx/view


can be deployed at
https://sheltered-spire-79865.herokuapp.com/
link to github https://github.com/Afrema90/Progressive-Web-Applications-PWA-Challenge-Text-Editor
