# Prerequisite : 

* Install the Nodejs.
* To store the data in MongoDB , create a free MongoDB account from below URL
  https://cloud.mongodb.com/

# Setup

* Clone the repo in your local folder.
* Run the below command to install the supporting node modules
  - npm install
* Go to your salesforce and create the connected app.
* Open the web-server.js file and update the callback url ,client id and Client Secret from your connected app.
* Open the uer-agent.js file and update the callback url and cunsumer key.
* If you are running the user-agent flow and add the callback URL in **CORS** section of Salesforce. 
* Update the web-server.js file with MongoDB url to store the account data in database.

# RUN WEB-Server Flow

* Open the temminal and run the below command.
   * node web-server.js
   
# RUN User-Agent Flow

# Notes
* Using EJS (Embedded JavaScript) template to genrate the html content.

* Open the temminal and run the below command.
   - node user-agent.js
   
