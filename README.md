# Eat-Da-Burger!

## Table of Contents 
1. [Overview](#overview)
2. [Technologies](#technologies)
3. [Local Installation](#installation)
4. [App Display](#display)

<a name="overview"></a>
## Overview 
Eat-Da-Burger! is a burger logger with MySQL, Node, Express, Handlebars and a homemade ORM. The app is formulated following the MVC design pattern; use Node and MySQL to query and route data in your app, and Handlebars to generate your HTML.

<a name="technologies"></a>
## Technologies

* JavaScript/jQuery
* Node.js
* Node packages: Express, Path
* MySQL database
* Handlebars
* ORM
* MVC design pattern

<a name="installation"></a>
## Local Installation

Clone Eat-Da-Burger to your local git repo with the following command in the terminal:

> git clone https://github.com/hyxhuynh/burger

The Eat-Da-Burger files should now be downloaded into your folder.

Or check out the app at: https://radiant-island-44993.herokuapp.com/

<a name="display"></a>
## App Display
* Eat-Da-Burger! is a restaurant app that lets users input the names of burgers they'd like to eat.
* Whenever a user submits a burger's name, the app will display the burger on the left side of the page -- waiting to be devoured.
* Each burger in the waiting area also has a `Devour It!` button. When the user clicks it, the burger will move to the right side of the page.
* The app will store every burger in a database, whether devoured or not.

![Demo](/public/assets/img/Eat-Da-Burger.png)