# w27BadBank

Project Title: The title of your project.
Description/Motivation: The reasons why this project exists, including the answers to pertinent questions such as whom does it help, why did you build it, and what business or personal problem does it solve.
Installation Guidelines: fork, git clone, run npm install, install Docker Desktop making sure it's up to date.  Run Docker $ docker run -p 27017:27017 --name badbank -d mongo

Once it is running, check that it is functioning by navigating to localhost:27017 in a browser. You should see the following:

Note: If you do not complete this activity in one sitting and need to restart your MongoDB Docker container, you may need to remove the previously created “bad bank” container with the command: docker rm /badbank before re-running the command above.

Step 2: Test MongoDB
run the node mongo_test.js command in the same directory as the file to test out your Docker MongoDB instance. 

Note: You will need to both initialize a node project in the same folder and run the npm install mongodb command in order to run the file as is.

You should then see something like the following as the terminal output:

Connected successfully to server
Collection: []
Document insert


Next, use Robo 3T to check the contents of your MongoDB database. 

To verify that the test has been successful, you will need to download Robo 3T (Links to an external site.), which will allow you to browse your MongoDB database.
"Create" connection.  use default settings 27017 and save on  Direction Connection type address localhost: 27017 

Screenshots: coming soon
Technology used: MERN stack full stack.  Mongo, Express, React, Node.js, will consider firebase, mongoose, next.js
Features: landing page, login, create acc, balance, deposit, withdraw, all data
License: MIT
