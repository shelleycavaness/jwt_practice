

### - What is the version of Material-UI used for this course ?
This course uses v4.0.0 of Material-UI library

### - What is the React version need for this course ?
********************
We are using `react` >=16.8.0 and `react-dom` >= 16.8.0 at all times. All the dependecies needed to run this project will be available in package.json
file. You do not have to worry about finding the peer dependencies to run the project. 
All you need are the 2 following commands to get started as long as you have the right version of Node.

`npm install`

`npm start`

Alternatively, you can also use `yarn` command.

`yarn install`

`yarn start`


### - Do I need Webpack or Babel to run this project ?
No, You don’t need to install or configure tools. You just need the LTS version of Node.js and the npm version that comes with it. 
They are preconfigured and hidden so that you can focus on the code.

### - Which browser are we using for this course ?
We shall be using the latest version of Chrome as of today. Be sure to install/update Chrome on your computer.

### - How do I open Chrome Browser in Mobile View ?
- To open Chrome in Mobile view mode using Mac, press ```Command+Option+i```

### - How do I run the Client application in browser?
To run the app in the development mode,
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.
We are using Chrome Developer console in this course.

### Where is the Node server running?
Your server is will run at port 5000 and the URL for server APIs is [http://localhost:5000](http://localhost:5000).

### Is it mandatory to use Material-UI library for Styling?
No, feel free to use simple CSS for styling or any other styling library you like. The focus of this course is to 
understand the use of JSON Web Token to secure the backend APIs and the front end styling is just an 
extra beautification layer.  

### How to test the backend APIs using CLI and Postman?
Install  [Postman](https://www.postman.com/) on your machine and start creating the collections where you 
can keep track of the API end points currently under testing. They have extensive documentation on how to use the tool.
in case your are interested. 

### I am running into issues when installing `bcrypt` library. How do I resolve them?
Install `bcrypt` from `npm` using the commands below. 
Note that `node-gyp` should be installed globally for the most recent Operating System on Mac which is Catalina.
```bash
npm install -g node-gyp
npm install --save bcrypt
```

### What user credentials are used in the Bookie App?
Below are the credentials you may want to use when logging to the app as member or admin.

**Member** 
```bash
deeksha30
kdje89#$%
```

**Admin**
```bash
zenmade23
728193kfej**(
``` 

### How do I start the server?
Go inside the `server/` directory and run teh command below.
```bash
node server.js
```
**Note:** Make sure you restart your server each time you checkout a new branch for every module and for 
every code change in the server side code.  


# Git Branches
Checkout the branches listed below as you progress through different modules.

### MODULE 02
`module02_jwt_security`

### MODULE 03
`module03_jwt_security`

### MODULE 04
There are 2 git branches used in this module.

To send JWT in a Cookie, checkout  `module04_jwt_security_cookies`

To send JWT in Auth Header Bearer Token, checkout `module04_jwt_security_bearer_token` 

Below are the contents of `variables.env` file.
```
SECRET=")x2f-l-opsnd)w!!z2m7ykvony99pt@6@6m+=q2uk3%w8*7$ow"
ALGORITHM="HS256"
ISSUER="BOOKIE_ORG"
EXPIRY="1h"
```
 

### MODULE 05
`module05_jwt_security_bearer_token_client`

# Resources

- [Proxying API Requests in React Development](https://create-react-app.dev/docs/proxying-api-requests-in-development/)
- [JWT Debugger](https://jwt.io/)
- [RFC 7519 - JSON Web Token (JWT) - IETF Tools](https://tools.ietf.org/html/rfc7519)
- [Using HTTP cookies](https://developer.mozilla.org/en-US/docs/Web/HTTP/Cookies)
- [Decode JWT on the client using with jwt-decode](https://github.com/auth0/jwt-decode)
- [GitHub code samples for usage of JWT by Auth0](https://github.com/auth0/jwt-handbook-samples/blob/master/stateless-sessions/app.js)


Below are some good questions and answers by the community on StackOverflow.
- [Authentication: JWT usage vs session](https://stackoverflow.com/questions/43452896/authentication-jwt-usage-vs-session)
- [Where to save a JWT in a browser-based application and how to use it](https://stackoverflow.com/questions/26340275/where-to-save-a-jwt-in-a-browser-based-application-and-how-to-use-it)
- [JavaScript and third party cookies](https://stackoverflow.com/questions/3363495/javascript-and-third-party-cookies)
- [Which way to create cookie, by frontend or backend?](https://stackoverflow.com/questions/26082511/which-way-to-create-cookie-by-frontend-or-backend)
- [How does server return JWT token to the client?](https://stackoverflow.com/questions/51503024/how-does-server-return-jwt-token-to-the-client)

 
 


