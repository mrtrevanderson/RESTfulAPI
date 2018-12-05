# RESTfulAPI


Node_modules folder is ommitted


Before you start
------------------


-Make sure you have Node.js and MongoDB installed
-run **npm -v** and **mongo --version** to show the version installed on your machine

In your terminal--
-Create a folder named todoListApi **mkdir todoListApi**
-Navigate to folder **cd todoListApi**
-Create a package.json file or edit the one provided **npm init**


To run
-----------------

Add the api folder, package.json file and server.js file to the todoListApi folder

Setup the server by running **npm install --save-dev nodemon** and **npm install express --save**
*this will add the node_modules folder*

run **npm run start** in the terminal to start the server
install mongoose in separate terminal **npm install mongoose --save**

Start the MongoDB Server by running in your separate terminal **mongod**
restart you server in original server **rs**

Check the local host **http://localhost:3000/tasks** and make sure your server and DB are connected
You should see "[]" because nothing is added yet
If you see "Cannot GET /task" then it isnt connected


Use **Postman** application to check and debug the connection 


