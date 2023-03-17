# text-editor
  ![badge](https://img.shields.io/badge/license-MIT-blue.svg)
  ## Description
  This is a Progressive Web Application (PWA) built with Node, Express, CodeMirror, IndexedDB and webpack. It is currently deployed to Heroku <a href =https://text-editor87756.herokuapp.com> here </a>

  ![screenshot](/screenshot.jpg)

  ## Table of Contents
  * <a href="#installation">Installation</a>
  * <a href="#usage">Usage</a>
  * <a href="#license">License</a>

  ## Installation
  Before running this application, please ensure you have Node installed. Then, from the command line, run "npm i" to install all the required dependencies. You can run this application in development or production mode. Npm start will run the application in production mode and start the server so you can open the app on localhost3000. This will also build the dist folder from the webpack config.
  ## Usage
  Click the installation button to download an offline version. To see the service worker and manifest, in action open the DevTools in your browser and click the application tab. Inside the application tab, under Storage, view the IndexedDB database. Cache Storage (at the bottom of the Storage section) will show the items cached in "asset-cache" by the service worker. The see the caching strategy utilized by the service worker check out the src-sw.js file in the root directory.
  ## License
  This project is covered under an MIT license. 



