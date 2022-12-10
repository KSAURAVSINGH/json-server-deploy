<h1 align="center">
  <a href = "stellar-mandazi-188925.netlify.app">JSON-SERVER AS FAKE-API</a>
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

## Dependencies Used
Name | Version
--- | ---
json-server | ^0.17.0

## Resources
- https://blogs.sap.com/2021/01/14/how-to-create-a-fake-rest-api-with-json-server/
- https://spin.atomicobject.com/2022/06/07/api-json-server/#:~:text=JSON%20Server%20is%20an%20easy,can%20do%20with%20JSON%20Server.
