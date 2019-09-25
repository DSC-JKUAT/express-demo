# Express-demo
Basic Express application demonstrating setting up an express server, routing and views

# Getting started

*Ensure you have NodeJs and npm installed on your PC/laptop*

Head over to your terminal and move into your working/ projects directory and copy and paste the following: 

**Clone the repository from GitHub:**
```
git clone  https://github.com/DSC-JKUAT/express-demo.git
```
**Move into the folder containing the starter files**
```
cd express-demo
```
**Install the necessary dependencies**
```
npm install
```
**Run the application**
```
SET DEBUG=express-locallibrary-tutorial:* & npm start  #Windows
DEBUG=express-locallibrary-tutorial:* npm start #Linux and MacOS
```
Load [http://localhost:3000/ ](http://localhost:3000/ ) on your browser:

To enable server restart on file changes, install nodemon as a development dependency:
```
npm i --save-dev nodemon
```
Add a new script in the `package.json` file:
```
"scripts": {
    "start": "node ./bin/www",
    "devstart": "nodemon ./bin/www"
  },
  ```
  You can now start the server in a similar way as previously done
  ```
SET DEBUG=express-locallibrary-tutorial:* & npm devstart  #Windows
DEBUG=express-locallibrary-tutorial:* npm devstart #Linux and MacOS
```
