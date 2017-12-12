# MERN Example

This project contains starter code for a Mongo, Express, React, Node application. It's purpose is for beginners to get familiar with using the MERN stack to build a simple web application that requires a login screen. 

The tutorial for this source code can be found here (#TODO: insert link for tutorial). 

This tutorial has used the following projects as guidelines: 



This starter project also uses:

- **Webpack** to bundle its scripts
- **Passport** and **Javascript Web Tokens** (JWT) for authentication (username + password)
- **React-router** for using routes in the frontend 
- **Bootstrap** for responsive CSS design
= **Mongoose** as an ODM for mongodb

## Quickstart

1. Clone the repository. 

2. In the root directory of the app, run: 

    npm install
    npm run debug

## Deployment 

1. Build the frontend application for deployment:

    npm run build_frontend

2. To deploy to heroku: 

- set up a production MongoDB 
- everything should be set up to just `git push heroku master`
