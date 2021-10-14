# Budget-Tracker

  ## ![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)

  ## Description
  A web application that allows a user to add expenses and deposists to their budget tracker with or without an internet connection. The budget history is displayed in a graph and the data is stored on a MongoDB database. The app's files are cached in the browser, so the app works as expected even offline. Because there is no connection to communicate with the database, the offline edits to the data are stored through indexedDB in the browser and when the app gains a connection to the internet, the stored data is then fetched to the dataabase.

  The application is hosted on a server and stores data on a MongoDB database. Makes use of a few node modules to make the development easier, including: Express, Mongoose, and Morgan. This app makes use of:
  * Node.js and Express.js to create RESTful APIs
  * GET and POST routes to communiciate with the database 
  * MongoDB (noSQL) and Mongoose OMT for the database
  * Service-worker.js to cache to files to the browser

  ## Table of Contents
  * [Installation](#installation)
  * [Usage](#usage)
  * [License](#license)
  * [Contributing](#contributing)
  * [Questions](#questions)
  
  ## Installation
  To install Node.js, follow the documentation [Node.js](https://coding-boot-camp.github.io/full-stack/nodejs/how-to-install-nodejs)

  To install MongoDB, follow the documentation [MongoDB](https://docs.mongodb.com/manual/installation/)

  To install necessary dependencies, run the following command: 
  ```
  npm i
  ```
  
  ## Usage
  Access the webpage by going to the deployed site: [Budget-Tracker](https://frozen-bayou-66534.herokuapp.com/). 

  If you want to run this on a local server, set the path to the Progressive-Budget folder in the terminal. Run the server.js file by typing `npm start`. Go to http://localhost:3000 to acesss the site.
  
  ![BudgetTrackerSS](https://user-images.githubusercontent.com/83731627/137250861-97721e2b-644f-4413-90ab-879628dbe194.png)
![budget-tracker-runtime](https://user-images.githubusercontent.com/83731627/137250972-9bda5cce-75ca-49e6-b43f-484b4ad94722.png)
![budget-tracker-indexDB](https://user-images.githubusercontent.com/83731627/137250977-2ea1a08c-e02a-45be-8477-2bdeea526b4e.png)

  ## License  
  This project is licensed under the terms of the [MIT License](https://opensource.org/licenses/MIT).

  ## Contributing
   I am the sole author of this repo and I am not currently looking for contributors.

  ## Questions
  If you have any questions about the repo, open an issue or contact me directly at Gaitherdb@gmail.com. You can find more of my work at [Gaitherdb](https://github.com/Gaitherdb).
