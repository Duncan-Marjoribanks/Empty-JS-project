# A JS project template to avoid having to set up the most commonly used files and dependencies

### devDependencies included
  "mocha": "^5.2.0",
  "nodemon": "^1.17.5",
  "webpack": "^4.15.1",
  "webpack-cli": "^3.0.8"

### dependencies included
  "body-parser": "^1.18.3",
  "express": "^4.16.3",
  "mongodb": "^3.1.1"


**There are 3 helper files included:**

./client/src/helpers/pub_sub.js
*implements the PubSub pattern throughout the project*

./client/src/helpers/request.js
*makes requests from a specified API*

./server/helpers/create_router.js
*performs CRUD requests from a mongodb database*


## Comands

**The project will require 3 terminal tabs open to run implementing all functionality:**
npm run build
npm run server:dev
mongod

**To seed the database:**
mongo < server/db/seeds.js


## Reminders

* remember to require in PubSub when broadcasting
* remember to **export your modules**
* the CRUD here is super basic and may need to be mucked about with
* APIs may need access keys
* **write tests** in the specs directory
* CSS is not the enemy
* check dependancies
* the project opens in localhost:3000
