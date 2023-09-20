# PWA Text Editor

  [![License](https://img.shields.io/badge/License-MIT-orange.svg)](https://choosealicense.com/licenses/mit/)

  ## Description

  This project uses the `idb` node package and the `workbox` and  `webpack` plugins to build a text editor that runs in the browser and functions offline. The app has the following capabilities:

 * adding a database name, MySQL username, and MySQL password to an environment variable file connects to a database using Sequelize
 * opening the application in your editor shows a client server folder structure
 * running `npm run start` from the root directory starts up the backend and serves the client
 * running the text editor application from your terminal leads to your JavaScript files being bundled using webpack
 * running your webpack plugins generates an HTML file, service worker, and a manifest file
 * using next-gen JavaScript in your application lets the text editor still function in the browser without errors
 * opening the text editor, the IndexedDB has immediately created a database storage
 * entering content and subsequently clicking off of the DOM window saves the content in the text with IndexedDB
 * reopening the text editor after closing it retrieves teh content in the text editor from your IndexedDB
 * clicking on the Install button downloads the web application as an icon on your desktop
 * loading the web application results in a registered service worker using workbox
 * registering a service worker leads to your static assets being pre cached upon loading along with subsequent pages and static assets
 * deploying to Heroku has the proper build scripts for a webpack application

  ## Table of Contents
  - [Installation](#installation)
  - [Usage](#usage)
  - [Credits](#credits)
  - [License](#license)
  - [Contribute](#contribute)
  - [Tests](#tests)
  - [Questions](#questions)
  
  ## Installation

  1. If not already installed, download [Node.js](https://nodejs.org/en/download) and [Git](https://git-scm.com) (if using Windows)
  
  2. Clone the `pwa-text-editor` repository to your machine from the command line (Git Bash on Windows) or terminal (Mac)
  
  ```bash
      git clone git@github.com:pinkhaze/pwa-text-editor
  ```

  3. In your code editor of choice, navigate to the `pwa-text-editor` repository

  4. Open a new terminal and type the following command to initialize a new Node project:

  ```bash
      npm install
  ```

  9. Start the application by entering the following command:

  ```bash
      npm run start
  ```

  ## Usage

  [See the deployed application here](https://pwa-jate-23-cdbe4e800d92.herokuapp.com/)

![J A T E - Google Chrome 9_20_2023 6_00_36 AM](https://github.com/pinkhaze/code-refactor/assets/55771228/1465dace-1cd4-4144-906c-ad8d49c12de4)

![J A T E - Google Chrome 9_20_2023 6_02_19 AM](https://github.com/pinkhaze/code-refactor/assets/55771228/eb0aa889-be48-448a-819d-dad16b1d3aae)

![J A T E - Google Chrome 9_20_2023 6_02_28 AM](https://github.com/pinkhaze/code-refactor/assets/55771228/1c83dfba-00da-4435-96c5-606e52007606)

![J A T E - Google Chrome 9_20_2023 6_01_26 AM](https://github.com/pinkhaze/code-refactor/assets/55771228/f33f525d-8d30-4773-a0e5-c1081f1b1b37)

  ## Credits

  [Module 19 Mini Project](https://git.bootcampcontent.com/University-of-Minnesota/UofM-VIRT-FSF-PT-04-2023-U-LOLC-ENTG/-/tree/main/19-PWA/01-Activities/28-Stu_Mini-Project)

  ## License

  [MIT License](https://choosealicense.com/licenses/mit/)

  ## Contribute

  NA
  
  ## Tests

  NA

  ## Questions

  Check out the other projects on my GitHub profile at [pinkhaze](https://github.com/pinkhaze).
