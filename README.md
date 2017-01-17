# Survey app
This is one online survey app from Lehigh CSE303 course.

## Features:
1. Allows users to make an account and login or login with google account!
2. Allows admin to release survey question and user to answer question.
3. Store user information in MongoDB online
4. Implement cache with Memcached online.
4. Calculate and show survey result automatically.

## Required Software
* [MongoDB](https://www.mongodb.com/)
* [Memcached](https://memcached.org/)
* [Git](https://git-scm.com/)
* [Node/NPM](https://nodejs.org/en/)

## How to run?
1. Install MongoDB and Memcached on your local device or AWS and run them.
2. Clone the repository.
3. `cd` to the newly cloned project.
4. Run `npm install` in command line to get the required dependencies.
5. `cd` to config folder to modify the configure of MongoDB, Memcached and Google Registration.
6. `cd` back to project and run `node server.js`.

## What to do when everything is up and running!
1. Go to `your IP:8080/login` to create an account by clicking on Sign Up button or login with Google account.
2. Or login with Google account or login with existing account. 
3. Create an Survey.
4. Go to `your IP:8080` to begin answer questions.

## Technology stack
HTML5, CSS3, Javascript, Bootstrap, AngularJS, MongoDB, Memcached, Google authentication

## Resources:
- [Angular Docs](https://docs.angularjs.org/guide)
- [Sass Guide](https://responsivedesign.is/develop/getting-started-with-sass)
- [W3school](http://www.w3schools.com/)
- [MongoDB](https://www.mongodb.com/)
- [Memcached](https://memcached.org/)
- [Google Node authentication](https://scotch.io/tutorials/easy-node-authentication-google)
