# Express.js

#### learnig notes on express:

- use Express Application Genrator to create skeleton website and applicatio
- start/stop node serveer
- use DB to store you application data
- create routes for requesting ino, templates('views')to render the dataas html to be displayed 
- work with forms
- deploy to prod

if and when you get stuck [visit](https://github.com/mdn/express-locallibrary-tutorial)


oder of creating project
`express project-name --view=templateEngine`
running the skelepton site
`cd express-project-name`
`npm install`
running the app
cmnd below is mac only
`DEBUG=express-locallibrary-tutorial:* npm start`

Then load `http://localhost:3000/` in your browser to access the app.

use `nodemon` to automate the process of restarting the server

locally as dev dependency 
`npm install --save-dev nodemon`

globally on the machine
`npm install -g nodemon`

