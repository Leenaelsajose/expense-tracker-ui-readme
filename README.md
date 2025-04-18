# Getting Started with Create React App

- This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

- This application is hosted using Firebase.

  - If you want to debug and run the app locally 

    - delete the .firebase folder and its contents
    - point the terminal to directory expense-tracker-ui and first build the project using `npm run build`
    - once the project builds successfully run the command `npm start` to run the app in development mode
 - For hosting the app using firebase follow the below steps
   - run `npm install` to install all the package dependencies
   - run `npm run build` to build the project
   - run `npm install -g firebase-tools`  to install Firebase Command Line Interface
   - run `firebase init hosting` to initialize firebase and to select firebase hosting
   - pick the project or select Y if initializing within an existing project
   - What do you want to use as your public directory? (public)  - pick the default value of public
   -  Configure as a single-page app (rewrite all urls to /index.html)? - pick Y
   -  Set up automatic builds and deploys with GitHub? - pick N
   - File public/index.html already exists. Overwrite? - pick Y
   - run `npm run build` again
   - run the command `firebase deploy --only hosting`
   - once the deploy is done the below url would be part of the output
        - Project Console: https://console.firebase.google.com/project/leena-final-project/overview
        - Hosting URL: https://leena-final-project.web.app
   -  https://leena-final-project.web.app is the url for the app, open a browser and paste the url and hit enter the app should load.

