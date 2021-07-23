# Mailchimp Newsletter Sign Up Full Stack Website
In this repo, I have built a full stack web app using Node.js and Express that allows the users to sign up themselves for newsletters. The Name and Email address of the user entered in the frontend are saved to the mailchimp list directly using the Mailchimp API.


## Weather App Demo
![Alt Text](https://github.com/drdataSpp/Mailchimp-Newsletters-API-Web-App/blob/master/News%20Letter%20Demo.gif)


## What is this app about?

- This is a full-stack web app built using:
  - Front-End: HTML, CSS & Javascript
  - Back-End: Node.js & Express
  - MailChimp API 
 
- Input for the app: First and Last name of the user & Email Address of the user.
- Output from the app: Redirects the user to success or failure page.
- Backend process: Once the user have filled the signup form, their details will be directly stored in the MailChimp audience list via MailChimp API

## Steps to set-up web development environment using command prompt
1. Make a new directory: `mkdir DIRECTORY_PATH`
2. Change the current directory to the newly created directory: `cd NEW_DIRECTORY_PATH`
3. Create a new javascript file: `touch app.js`
4. Create a new HTML file: `touch index.html`
5. Create a new CSS file: `touch style.css`
6. initialize the npm: `npm init`
8. Install Express.js: `npm install express`
9. Install body parser: `npm install body-parser`
10. Install request: `npm install request`


## Steps to set-up Node.js and Express
`const express = require('express');` <br>
`const app = express();`

### To bind and listen the connections on the specified host and port.
`app.listen(PREFERRED_PORT_NUMBER);`

### To run the website
After performing the above steps and editing the contents in HTML, CSS and Javascript files: <br>
- Type in command prompt:
  - `node app.js` or
  - `nodemon app.js` 
  
- Open your preferred browser:
  - search for `localhost:PORT_NUMBER`
