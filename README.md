# Node Todo App

This demo app is adopted from Scott's tutorial at https://scotch.io/tutorials/creating-a-single-page-todo-app-with-node-and-angular.  The main objective for this demo is to show the following:
1. How to deploy nodejs app to Azure 
2. Azure MongoDB service can work with existing MongoDB and driver (mongoose in this case).


## Requirements

- [Node and npm](http://nodejs.org)
- MongoDB: This code is intended to use Azure DocumentDB service (https://azure.microsoft.com/en-us/documentation/articles/documentdb-protocol-mongodb/). You can use your own local or remote MongoDB database URI configured in `config/database.js`

## Installation
1. Clone the repository: `git clone https://github.com/harrchen/ToDo_MEAN.git`
2. Install the application: `npm install`
3. Place your own Azure DocumentDB (with MongoDB API) or MongoDB URI in `config/database.js`
3. Start the server: `npm start`
4. View in browser at `http://localhost:3000`

## Tutorial Series

This repo is modified from the Node Todo Tutorial Series on [scotch.io](http://scotch.io)


