# burger

Following the MVC design pattern, this app is design for a burger logger using MySQL, Node, Express, Handlebars and a homemade ORM.
This app is deployed to Heroku with MySql services.

Deployment Link https://nameless-shelf-77460.herokuapp.com

Key Topics

Template engines
Handlebars.js
Model-View-Controller
Object-relational mapping

Eat-Da-Burger! is a restaurant app that lets users input the names of burgers they'd like to eat.

Whenever a user submits a burger's name, this app will display the burger on the left side of the page -- waiting to be devoured.

Each burger in the waiting area also has a Devour it! button. 
When the user clicks it, the burger will move to the right side of the page.

This app will store every burger in a database, whether devoured or not.

Using the Model-View-Controller (MVC) configuration, the file structure is:

Directory structure

All the recommended files and directories from the steps above should look like the following structure:

.
├── config
│   ├── connection.js
│   └── orm.js
│ 
├── controllers
│   └── burgers_controller.js
│
├── db
│   ├── schema.sql
│   └── seeds.sql
│
├── models
│   └── burger.js
│ 
├── node_modules
│ 
├── package.json
│
├── public
│   └── assets
│       ├── css
│       │   └── burger_style.css
│       └── img
│           └── burger.png
│   
│
├── server.js
│
└── views
    ├── index.handlebars
    └── layouts
        └── main.handlebars




