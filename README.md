# TEQUILA API Doc.

Tequila API is an REST API that manage generic tags related to consumers of any kind of plataforms that provides Videos On Demand. This means that you can create tags, like what movies the consumer want to see in the future or what series he want to favorite. 

## Setup

First, you have to make sure that you have the following plataforms installed in your enviroment:

- * https://www.docker.com/products/docker-desktop : `Docker;`
- * https://nodejs.org/en/download/ : `NodeJS`;

Ti initialize the API in your local enviroment, you have to open your terminal, go to the root of the project and put the following comands:

Install all dependencies:
```npm install```

Initialize the server:
```npm start```

## Endpoints

Open endpoints require no Authentication.

* [Login](login.md) : `POST /api/login/`

