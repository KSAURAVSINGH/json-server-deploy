<h1 align="center">
  <a href = "https://cold-satin-dedication.glitch.me/">JSON-SERVER AS FAKE-API</a>
</h1>
JSON Server is an easy and quick-to-set-up module that you can use to fake or mock an API.

# Project Structure
```terminal
images/
.DS_Store
.gitattributes
.gitignore
LICENSE.md
README.md
db.json
package.json
server.js
yarn.lock
```
# Usage (run on your machine)

## Prerequisites
- [Node](https://nodejs.org/en/download/) ^14.15.4 or above
- [Yarn](https://yarnpkg.com/) ^1.22.19 or above

## Steps
- Clone the Repository
- Install the Dependencies
- Run the Project

## Clone the Repository
You can clone the repo or download the zip file.<br>
To clone:
```terminal
git clone https://github.com/KSAURAVSINGH/json-server-deploy.git
```

## Install the Dependencies
There is only one dependency we need to install - json-server<br>

**Install json-server**<br>
```termainal
yarn add json-server
```

## Run the Project
```terminal''
json-server --watch db.json
```

You should see a file named db.json created in the folder. When you run the server locally, it tries to search for the file (db.json) and if not found, it creates a file on its own with mock JSON data.<br>
<br>
It’ll run your server locally on http://localhost:3500<br>
To change the PORT, go to server.js file and change the port number mentioned there.

## Dependencies Used
Name | Version
--- | ---
json-server | ^0.17.0


## Visual Representation of Project
<img width="1440" alt="Screenshot 2022-12-10 at 3 00 01 PM" src="https://user-images.githubusercontent.com/55026380/206843593-3eeb42ad-4ee2-489e-a548-a0d478981e6b.png">
<img width="1440" alt="Screenshot 2022-12-10 at 3 00 30 PM" src="https://user-images.githubusercontent.com/55026380/206843677-65c9eda5-bc6a-44bd-b384-b633eba6e014.png">
<img width="1440" alt="Screenshot 2022-12-10 at 3 00 42 PM" src="https://user-images.githubusercontent.com/55026380/206843754-333d62d4-d9fb-4df4-8cbb-4065c8e64ae3.png">
<img width="1440" alt="Screenshot 2022-12-10 at 3 00 54 PM" src="https://user-images.githubusercontent.com/55026380/206843888-6153c9cb-1ea9-46d9-8a71-b49438e4fb41.png">


## Resources
- https://blogs.sap.com/2021/01/14/how-to-create-a-fake-rest-api-with-json-server/
- https://spin.atomicobject.com/2022/06/07/api-json-server/#:~:text=JSON%20Server%20is%20an%20easy,can%20do%20with%20JSON%20Server.

## Contact Me
kumarsauravsingh1234567890@gmail.com