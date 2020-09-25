# Unit 14 Sequelize Homework: Reverse Engineering Code

# Project Explantation
```
1. A simple application to allow user to setup acount
2. MySQL as the database, Sequlize as Models, express.js as routes, and bcryptjs to keep user's password safety
```

## File Sturcture

```
Develop
├── config
│   ├── middleware
|   |   └── isAuthenticated.js
|   ├── config.json
|   └── passport.js
├── models
│   ├── index.js
|   └── user.js
├── public
│   ├── js
|   |   ├── login.js
|   |   ├── members.js
|   |   └── signup.js
|   ├── stylesheets
|   |   └── style.css
|   └── html
├── routes
|   ├── spi-toutes.js
|   └── html-routes.js
├── server.js
└── package.json
```

## Install
* Change the directory to Develop folder
```
$ npm install
```

![npminstall](./gif/npminstall.gif)

## Usage
* Change the directory to Develop folder
```
$ node server.js
```

![nodeserver](./gif/nodeserver.gif)

* Sign up and Login

![loginlogout](./gif/loginlogout.gif)

### Language
```md
Javascrpit
Node.js
Express.js
Sequlize
MySQL
bcrypt.js
```