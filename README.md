# REACT-EXPRESS BOILERPLATE WITH EXTERNAL MYSQL ACCESS

This repository was made to complement the following tutorial:

https://medium.com/@carloscuba014/building-a-react-app-with-a-express-back-end-in-the-same-project-with-external-access-to-a-mysql-e06ef83c257d

# Start Here

First install the npm modules by running `yarn install` from the root project folder C:/Users/youraccount/folder/react-fantasy-football/

After doing so you should see a new folder called /node_modules/

Open up the package.json file and take a look at the list of commands you can utilize to start the nodejs server and react application.

Under the "scripts" section you will see this:

``
"scripts": {
  "start": "react-scripts start",
  "build": "react-scripts build",
  "test": "react-scripts test",
  "eject": "react-scripts eject",
  "server": "nodemon -r dotenv/config app.js",
  "client": "react-scripts start",
  "dev": "concurrently \"yarn run server\" \"yarn run client\""
},
``

To start the nodejs express server, open a command line prompt and cd into the root project folder. Run `yarn server`

To start the react application, open a NEW command line prompt and cd into the root project folder. Run `yarn start`

The application should open a browser window and display the contents of the application.
