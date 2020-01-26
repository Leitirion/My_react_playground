
### Frontend project with react and surge.
[![CircleCI](https://circleci.com/gh/Leitirion/My-circleci-cypress-ui-automation.svg?style=svg)](https://circleci.com/gh/Leitirion/My-circleci-cypress-ui-automation)

### Table of Contents

- Maintainers:

  [github.com/mikementor](https://github.com/mikementor)

  	
		
  [github.com/leitirion](https://github.com/leitirion)
	 
- How to run and publish
- How to install

## How to run and publish
1. For test project and see work it or not, type ```npm run start``` (this show your project on your localhost)
2. For manually build project to test machine on surge.sh or on your domen use ```npm run build```
3. After test succeed, use ```firebase deploy``` to build to firebase or to your domen.

## How to install
1. Run the following command to install firebase-tools.
```npm install -g firebase-tools```
2. When thats finished, run the following command to login to firebase
```firebase login```
3. After you’ve successfully logged in run this command to initialize firebase in your react-app (make sure you’re in your project directory):
```firebase init```
4. For React-Redux:
```npm install react-redux```
5. Let’s also install Redux Thunk. It is a very useful middleware that allows you easily create async actions:
```npm install redux-thunk```
6. For client side routing let’s install React Router. It will allow us to setup our login page and protected sign-in area:
```npm install react-router-dom```
7. And finally, lets install firebase which allows to interact with firebase within react app.
```npm install firebase```
8. For Material-UI:
```npm install @material-ui/core```
9. Install the material icon library:
```npm install @material-ui/icons```

