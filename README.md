## REST API POSTMAN Test Automation Framework 
==================================================================

## Overview
* This is simple project to showcase Api Test Automation Framework in CLI using Postman, Newman and basic script.
* **Skills:** Api Test Automation
* **Languages:** JavaScript/ Node.JS / Newman
* **SCM:** Git
* **Assertion Lib:** Chai, Expect, Should

## Setup
* Download [javascript-api-mocha](https://github.com/happyali/techTask.git) project from GitHub
* Install latest [Node.JS](https://nodejs.org/en/download/)
* Install latest [Visual Studio Code](https://code.visualstudio.com/download)

## Execution
* Open Terminal window and Navigate to Test_Framework Directory in the code editor
* naivgate to folder 'Rest_api_postman' (cd Rest_api_postman)
* Install latest [Newman] cli runner (npm install -g newman)

* Run command: " newman run Runner_Qantas_Suite.postman_collection.json -e Runner_dev_test.postman_environment.json -d test_data.json -n 4 -r html "
    where


| Runner_Qantas_Suite.postman_collection.json | export of test request collection as **json** |
| :---: | :---: |
| Runner_dev_test.postman_environment.json | export of test environment collection |
|test_data  | test data file name|
|n   | number of interation count (optional as it will run all by default)|
|r   | reporting tag|

* This run command wont show anything in console but will create a new folder named as "Newman" at root directory and a file with latest timestamp.
## Sample API Test Scenarios
    
    1. Call End point to get Weather details with respect to LOCATION (Lat, Log) 
    2. Call End point to get Weather details with respect to POSTCODE

## Note
* For future update, export of updated collection('s) is mandatory.
   
