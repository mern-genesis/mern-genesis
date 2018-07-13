![mern-genesis](static/img/MernLogo1.jpg)


# MERN Genesis
[![HitCount](http://hits.dwyl.com/{L-Figgins13}/{Genesis}.svg)](http://hits.dwyl.com/{L-Figgins13}/{Genesis})
[![JavaScript Style Guide: Good Parts](https://img.shields.io/badge/code%20style-goodparts-brightgreen.svg?style=flat)](https://github.com/dwyl/goodparts "JavaScript The Good Parts")
[![Node version](https://img.shields.io/node/v/[NPM-MODULE-NAME].svg?style=flat)](http://nodejs.org/download/)
[![Build Status](https://travis-ci.org/{L-Figgins13}/{Genesis}.png?branch=master)](https://travis-ci.org/{L-Figgins13}/{Genesis})
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)

**mern-genesis** is a scaffolding tool which aims to create a starting point for developing **Isometric JavaScript Applications** and **Progressive Web Application**'s using the **MERN** technology stack: **(MongoDB, Express, React, Node)**. 

In addition to **MERN**, this scaffolding project also includes several other technologies to ease development time, technologies such as **Socket.io** for real time events, **Material UI** for quick design templating, and **Redux** for state management, among others. 

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

* [Website](www.mern-genesis.github.io)
* [Documentation](www.mern-genesis.github.io/documentation)
* [Discussions](www.mern-genesis.github.io/forum)


### Prerequisites
For the project to work properly you will need:

[MongoDB & (Optional) Mongoose](https://www.mongodb.com/)

[NodeJS (v8.11 or higher)](https://nodejs.org/en/)


### Installing
A step by step series of examples that tell you how to get a development environment running

1. ```npm install -g mern-genesis```

2. ```genesis init my_app_name```

3. ```cd my_app_name```

4. ```npm install```

5. ```npm run watch-server```

6. ```npm run watch```

7. ```npm start```


**Note :** Please make sure your MongoDB database is up and running first. For MongoDB installation guide, please reference this MongoDB
[installation guide](https://docs.mongodb.org/v3.0/installation/).


### Available Commands

```

   - npm run watch-server -  starts the server with nodemon watching.
   - npm run watch - starts watching full project.
   - npm start - starts development app at localhost:3000, server at localhost:8000.

```


## Running the tests
- Coming Soon


## File Structure
```
.
└── mern-genesis
    ├── __tests__                    // all the tests for mern-genesis
    |   ├── components               // sub components of this module
    |   |   ├── Post.spec.js
    |   |   ├── PostList.spec.js
    |   |   ├── PostItem.spec.js
    |   |   └── PostImage.spec.js
    |   ├── pages
    |   |   ├── PostPage.spec.js
    |   |   └── PostViewPage.spec.js
    |   ├── PostReducer.spec.js
    |   └── PostActions.spec.js
    ├── client                   
    |   ├── auth.js
    ├── config                   
    |   ├── index.json
    ├── dist                   
    |   ├── server.bundle.js
    |   ├── server.bundle.map.js
    ├── server
    |   ├── middleware
    |   |   ├── auth-check.js
    |   ├── models
    |   |   ├── ExampleModel.js
    |   ├── passport
    |   |   ├── local-login.js
    |   |   ├── local-signup.js
    |   ├── routes
    |   |   ├── api.js
    |   |   ├── auth.js
    |   ├── auth-check.js
    |   ├── broadcast.js
    |   ├── constants.js
    |   ├── db.js
    |   ├── logger.js
    |   ├── server.js
    |   └── template.js
    ├── src
    |   ├── blocks
    |   |   ├── exampleblock.js
    |   ├── container
    |   |   ├── examplecontainer.js
    |   ├── elements
    |   |   ├── exampleelements.js
    |   ├── App.jsx
    |   ├── index.js
    ├── static
    |   └── img
    |   └── audio
    |   └── video
    ├── .gitignore
    ├── README.md
    ├── CONTRIBUTING.md
    ├── LICENSE.txt
    ├── package-lock.json
    ├── package.json
    ├── webpack.config.js
    └── webpack.server-config.js

```

**Webpack Configs**

MERN GENESIS uses Webpack for bundling modules. There are four types of Webpack configs provided:
 - **webpack.config.dev.js** for development
 - **webpack.config.prod.js** for production
 - **webpack.config.server.js** for bundling server in production
 - **webpack.config.babel.js** for babel-plugin-webpack-loaders for server rendering of assets included through webpack.

The Webpack configuration is minimal and beginner-friendly. You can customise and add more features to it for production builds if you would like.

**Server**

MERN GENESIS uses express web framework. Our app sits in server.js where we check for NODE_ENV.
If NODE_ENV is development, we apply Webpack middlewares for bundling and Hot Module Replacement.


## Front End Development
This scaffolding uses material UI for rapid design prototyping and styled components for modern web component styling. More information on this will be added shortly.


## Deployment
- Coming Soon!

## Built With
* [MongoDB]( https://www.mongodb.com/) - NoSQL Database
* [Express]( https://expressjs.com/) - Server Middleware
* [React](https://reactjs.org/) - Front End Web Technology
* [NodeJS]( https://nodejs.org/en/) - Npm and General Project Structure
* [Socket.io]( https://www.socket.io) - Real-Time Events
* [Styled Components](https://github.com/styled-components/styled-components) - General Component Styling
* [Material UI](https://material-ui.com/) - Design Prototyping


## Contributing 
[![contributions welcome](https://img.shields.io/badge/contributions-welcome-brightgreen.svg?style=flat)](https://github.com/dwyl/esta/issues)
Please read [CONTRIBUTING.md](https://gist.github.com/PurpleBooth/b24679402957c63ec426) for details on our code of conduct, and the process for submitting pull requests to us.


## Versioning
We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/your/project/tags). 


## Authors
* **Logan Figgins** - *Designer & Developer* - @github/L-Figgins13 - [MERN-GENESIS](https://github.com/L-Figgins13)
* **Zack Watkins** - *Designer & Developer* - @github/TheByteForge - [MERN-GENESIS](https://github.com/TheByteForge)

See also the list of [contributors](https://github.com/your/project/contributors) who participated in this project.


## License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details


## Acknowledgments
* Coming Soon