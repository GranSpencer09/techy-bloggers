# Techy-Bloggers

## Description

This application is a CMS-style blog website, where users can publish blog posts and comment on other posts as well. The app is also deployed on Herkou. Other features in this app are the MVC paradigm in its structure, Handlebars.js as the templating language, Sequelize as the ORM, and the express-session npm package for authentication.

Blogs are great ways for members of a community to connect and share! In building this, all types of users as able to securely login and connect with other users by browsing posts.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Credits](#credits)
- [License](#license)

## Installation

    1. Navigate to the code repository
    2. Press the green code button, located near the about section
    3. Copy either the HTTPS, Git CLI, download the zip, open with GitHub desktop, or copy the SSH link.
    4. Depending on download method, use Git, executable, or the desktop application to open the content files.
    5. All of the content of the repository will be available after completion of the previous state.

## Usage

After installing the application or loading the deployed Heroku link (https://sheltered-meadow-63483.herokuapp.com/login), you'll need to sign-up to begin. Once that's done, you're free to broswer posts made by other users and make your own.

![Login page](/images/Screen%20Shot%202022-10-16%20at%2012.27.37%20PM.png)

![Posts](/images/Screen%20Shot%202022-10-16%20at%2012.26.57%20PM.png)

![Create a post](/images/Screen%20Shot%202022-10-16%20at%2012.31.43%20PM.png)

## Features

This application’s folder structure follows the Model-View-Controller paradigm. It also uses Handlebars.js, MySQL2 and Sequelize to connect to a MySQL database for the Models, and to create an Express.js API for the Controllers. The app also uses the dotenv package, bcrypt package for hashing passwords, and the express-session and connect-session-sequlelize packages for authentication.
