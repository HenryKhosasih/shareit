# ShareIt

Share your memorable experience with the world

## URL

https://main.d3eez67dzgxag8.amplifyapp.com

## Description

A responsive full stack web application that allow users to:

- Register for a new account
- Login as current member
- View all posts
- View my posts
- Add new posts
- View detailed information of selected post
- Sign out

## Technology used

ShareIt is fully built and deployed in the AWS cloud environment using:

- Cloud9 for setting up and configuring application code in Linux environment
- Amplify for front-end and back-end integration (by automating services creation listed below using CloudFormation)
- AppSync for defining GraphQL API schema
- Cognito User Pool for user authentication
- S3 for storing uploaded images and development code
- DynamoDB for storing posts data
- React JS framework

## Screenshots

- [ShareIt page with one post](/screenshots/shareit-post.PNG)
- [ShareIt page to add new post](/screenshots/shareit-add.PNG)
- [ShareIt page with many posts](/screenshots/shareit-posts.PNG)
- [More details on a post](/screenshots/shareit-detailed.PNG)

## Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Available Scripts

In the project directory, you can run:

### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!

See the section about [deployment](https://facebook.github.io/create-react-app/docs/deployment) for more information.

### `npm run eject`

**Note: this is a one-way operation. Once you `eject`, you can't go back!**

If you aren't satisfied with the build tool and configuration choices, you can `eject` at any time. This command will remove the single build dependency from your project.

Instead, it will copy all the configuration files and the transitive dependencies (webpack, Babel, ESLint, etc) right into your project so you have full control over them. All of the commands except `eject` will still work, but they will point to the copied scripts so you can tweak them. At this point you're on your own.

You don't have to ever use `eject`. The curated feature set is suitable for small and middle deployments, and you shouldn't feel obligated to use this feature. However we understand that this tool wouldn't be useful if you couldn't customize it when you are ready for it.

## Working in progress

- Enable users to comment on posts
- Enable users to like posts
