# Getting Started with Create React App

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## How to run this project

In the project directory, run follow scripts:

### `npm install -g json-server`
Install json server for load English words dictionary.

### `json-server ./dataset/db.json --port 3001`
Start the json server and load the English words dictionary.

### `npm install`
Install all relative dependencies.

### `npm run start`

Runs the app in the development mode.\
Open [http://localhost:3000/home](http://localhost:3000/home) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

# Writeup
## Some general writeup:
#### What we implement:
 - core game logic
 - word validation
 - input validation (too lone / too short)
 - home page
 - game page (hard / normal mode)
 - restart button
 - rule page
 
#### About testing:
When testing our project, you can press F12 to open the browser console to view the answer. Given that we added word validation, there are at least 1000 words in the DB, and your test can be a pain (as we were), so I added this cheat for a quicker test.


## What were some challenges you faced while making this app?
For us, the biggest challenge was the game logic and how to pass props between components. Fortunately, one student shared a article about React Hooks in week8 discussion, which provided us with an effective reference. In addition, we have done a lot of research on game logic, and our project has made references to the following:
[references](https://kennethscoggins.medium.com/how-to-build-wordle-using-reactjs-and-about-200-lines-of-sloppy-code-3da3ef47013f)
[references](https://www.youtube.com/watch?v=s-1vuA92RJY)
[references](https://www.reactnativeschool.com/build-a-wordle-clone-with-react-native)

## Given more time, what additional features, functional or design changes would you make

If given more time, we want to add a game mode that allows the player's friends to propose a random English word and let the player guess it on our website. It can increase interactivity between friends and add more fun to the game. We will also add more styling work. Now our webpage is a bit "plain". Also, the example keyboard with input logging seems like a good idea. Given the extra time, we'll try to implement that keyboard.


## What assumptions did you make while working on this assignment?


## How long did this assignment take to complete?

1 week in total.

## Other Available Scripts

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

## Learn More

You can learn more in the [Create React App documentation](https://facebook.github.io/create-react-app/docs/getting-started).

To learn React, check out the [React documentation](https://reactjs.org/).

### Code Splitting

This section has moved here: [https://facebook.github.io/create-react-app/docs/code-splitting](https://facebook.github.io/create-react-app/docs/code-splitting)

### Analyzing the Bundle Size

This section has moved here: [https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size](https://facebook.github.io/create-react-app/docs/analyzing-the-bundle-size)

### Making a Progressive Web App

This section has moved here: [https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app](https://facebook.github.io/create-react-app/docs/making-a-progressive-web-app)

### Advanced Configuration

This section has moved here: [https://facebook.github.io/create-react-app/docs/advanced-configuration](https://facebook.github.io/create-react-app/docs/advanced-configuration)

### Deployment

This section has moved here: [https://facebook.github.io/create-react-app/docs/deployment](https://facebook.github.io/create-react-app/docs/deployment)

### `npm run build` fails to minify

This section has moved here: [https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify](https://facebook.github.io/create-react-app/docs/troubleshooting#npm-run-build-fails-to-minify)
