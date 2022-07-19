# Book-Search-Engine

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)

## Table-of-Contents

- [Description](#description)
- [Deployed Site](#deployed-site)
- [Features](#features)
- [Technologies](#technologies)
- [Future Development](#future-development)
- [Credits](#credits)

## Description

This is my nineteenth challenge assignment for the University of Oregon Coding Bootcamp 2022. In this project, I integrate a GraphQL API into a fully functioning book engine that was built using the MERN stack, replacing the previous RESTful API.

## Deployed Site

Follow [this link]([insert later]) to view and use our site!

## To-Do:

- npm init and install all dependencies
- Setup all dependencies in all package.json (root, server, client)
- Setup an apollo server to use GraphQL queries and mutations to fetch and modify data, replacing the existing RESTful API
- Modify the existing authentication middleware so that it works in the context of a GraphQL API
- Create an Apollo Provider so that requests can communicate with an Apollo Server
- User Story
    ```
    GIVEN a book search engine
    WHEN I load the search engine
    THEN I am presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button
    WHEN I click on the Search for Books menu option
    THEN I am presented with an input field to search for books and a submit button
    WHEN I am not logged in and enter a search term in the input field and click the submit button
    THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site
    WHEN I click on the Login/Signup menu option
    THEN a modal appears on the screen with a toggle between the option to log in or sign up
    WHEN the toggle is set to Signup
    THEN I am presented with three inputs for a username, an email address, and a password, and a signup button
    WHEN the toggle is set to Login
    THEN I am presented with two inputs for an email address and a password and login button
    WHEN I enter a valid email address and create a password and click on the signup button
    THEN my user account is created and I am logged in to the site
    WHEN I enter my account’s email address and password and click on the login button
    THEN I the modal closes and I am logged in to the site
    WHEN I am logged in to the site
    THEN the menu options change to Search for Books, an option to see my saved books, and Logout
    WHEN I am logged in and enter a search term in the input field and click the submit button
    THEN I am presented with several search results, each featuring a book’s title, author, description, image, and a link to that book on the Google Books site and a button to save a book to my account
    WHEN I click on the Save button on a book
    THEN that book’s information is saved to my account
    WHEN I click on the option to see my saved books
    THEN I am presented with all of the books I have saved to my account, each featuring the book’s title, author, description, image, and a link to that book on the Google Books site and a button to remove a book from my account
    WHEN I click on the Remove button on a book
    THEN that book is deleted from my saved books list
    WHEN I click on the Logout button
    THEN I am logged out of the site and presented with a menu with the options Search for Books and Login/Signup and an input field to search for books and a submit button
    ```
- Test all functionality
- Finish Readme
- Deploy to Heroku and connect MongoDB database
- Turn in Project

## Features

This is how the front-end webpage appears to viewers. It is responsive, adapting to multiple screen sizes.

<p align="center">
<img alt="A screenshot of the homepage of Book Search. A list of posts are shown in the main portion of the screen. There is also [insert later]" src="./assets/images/placeholder.jpg"/>
</p>

[insert later]

<p align="center">
<img alt="[insert later]" src="./assets/images/placeholder.jpg"/>
</p>

[insert later]

<p align="center">
<img alt="[insert later]" src="./assets/images/placeholder.jpg"/> 
</p>

## Technologies

- React.js
- CSS
- Bootstrap
- JavaScript
- Node.js
- npm
- [Express.js](https://expressjs.com/)
- MongoDB
- [Mongoose](https://mongoosejs.com/)
- [@apollo/client](https://www.npmjs.com/package/@apollo/client)
- [apollo-server-express](https://www.npmjs.com/package/apollo-server-express)
- [graphQL](https://graphql.org/)
- [JWT](https://jwt.io/)
- [bcrypt](https://www.npmjs.com/package/bcrypt)
- [Google Books API](https://developers.google.com/books)
- [concurrently](https://www.npmjs.com/package/concurrently)
- [nodemon](https://www.npmjs.com/package/nodemon)

## Future Development

In the future, I would like to add the following improvements:

- [insert later]

I'm always interested in refactoring code to improve it's functionality. If you would like to suggest your own improvements, you can reach our development team at the links below.

- <a href="mailto:ashlynn4567@gmail.com">Email</a>
- <a href="https://github.com/ashlynn4567">GitHub</a>
- <a href="https://www.linkedin.com/in/ashley-lynn-smith/">LinkedIn</a>

## Credits

This project was built with the help of the University of Oregon's Coding Boot Camp.

## Licensing

The application is covered under the following license: [MIT](https://opensource.org/licenses/MIT)