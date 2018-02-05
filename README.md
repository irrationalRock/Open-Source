# Phone Number Parser Release 0.1

This is a simple Node/Express application that parses, validates, and displays phone numbers using Google's [libphonenumber](https://github.com/googlei18n/libphonenumber) library.

## Updates
As of February 4, 2018, unit testing using [Jest](https://facebook.github.io/jest/) and [Supertest](https://www.npmjs.com/package/supertest)  have been implemented 

## To-do
- [x] Implement unit testing with [Jest](https://facebook.github.io/jest/) and [Supertest](https://www.npmjs.com/package/supertest) for various GET / endpoints.
- [ ] Continue implementing unit testing for POST /api/phonenumbers/parse/file/{file} endpoint.
- [ ] Reconstruct front-end to a React, Angular, or a Vue application.  Decision will be made once the previous to-do's have been completed.

## Working Demo on Heroku
https://osd600.herokuapp.com

## Setting up your environment
- In order for this application to work, you must have the latest [NodeJS](https://nodejs.org/en/download/) framework installed.
- [Visual Studio Code](https://code.visualstudio.com/) is the recommended IDE as it is being used for the current development of this application.

## Running the application locally
This application will run locally using port 8080.
Once your environment has been setup, follow these steps in order to run the application:
1. Install dependencies using npm
```
npm install or npm i
```
2. Run the application
```
npm start or node index.js
```

## Interacting with the application
Upon running the application, you will be taken to a homepage with details how to interact with the two API endpoints:

1. GET https://osd600.herokuapp.com/api/phonenumbers/parse/text/
   - d
2. GET https://osd600.herokuapp.com/api/phonenumbers/parse/file/

## Unit Testing
[Jest](https://facebook.github.io/jest/) is an open source unit testing framework by Facebook used to test Javascript codes.  It was developed with the philosophy of providing a "zero configuration" experience that allows developers to have a better testing experience.

Both Jest and Supertest are already included in the development dependencies, therefore not needing to install them.  To run the tests, simply follow this command:
```
npm test
```
And the results should output as follows:
```
test
```
