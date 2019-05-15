Eat-Da-Burger!

This is a restaurant app that lets users input the names of burgers they'd like to eat.

Node Express Handlebars
Overview
Find My Repository

I have built an application meant to log your burgers with MySQL, Node, Express, Handlebars and a homemade ORM. The app design pattern follows a MVC structure; using Node and MySQL to query and route data in the app, and Handlebars to generate the HTML.

Instructions
Whenever a user submits a burger's name, your app will display the burger on the left side of the page -- waiting to be devoured.

Each burger in the waiting area also has a Devour it! button. When the user clicks it, the burger will move to the right side of the page.

Your app will store every burger in a database, whether devoured or not.

Install These Packages

Go to my GitHub repo called burger and clone it to your computer.
Make a package.json file by running npm init from the command line.
Install the Express npm package: npm install express --save
Express
Install the Nodemon npm package: npm install nodemon --save
Nodemon
Install the MySQL npm package: npm install mysql --save
MySQL
Install the Body Parser npm package: npm install body-parser --save
Body Parser
Install the Handlebars npm package: npm install express-handlebars --save
Handlebars

Directory structure
All the recommended files and directories from the steps above should look like the following structure:

├── config
│   ├── connection.js
│   └── orm.js
│ 
├── controllers
│   └── burgers_controller.js
│
├── db
│   ├── schema.sql
│   └── seeds.sql
│
├── models
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   ├── assets
│   │   ├── css
│   │   │   └── burger_style.css
│   │   └── img
│   │       └── burger.png
│   └── test.html
│
├── server.js
│
└── views
    ├── index.handlebars
    └── layouts
        └── main.handlebars
