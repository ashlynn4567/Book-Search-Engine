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

- Test all functionality
- Record readme gifs and update features section
- Turn in Project

## Features

This is how the front-end webpage appears to viewers. It is responsive, adapting to multiple screen sizes. The main page shows new users a menu, with which they can search for books, login, or signup. If the user is logged in, the buttons they will see options to search for books, view their saved books, or logout.

[screenshot]

<p align="center">
<img alt="A screenshot of the homepage of Book Search. Users can search for books by filling out the search field, or they can login/signup by clicking the login/signup button." src="./assets/images/placeholder.jpg"/>
</p>

If the user selects "search for books," they are then presented with an input field to search for books. Clicking "submit" will return a list of search results, each featuring a book's title, author, description, image, and a link to that book on the Google Books site. If the user is logged in while searching for books, then an option appears for them to save a book to their account. By clicking on the save option, that book is added to the "Saved Books" page. Users can manage their saved books from this page by deleting that book from their saved books list.

[start from homepage while logged in, search for book, save book to saved books, delete book from saved books]

<p align="center">
<img alt="A demonstration gif showing the user searching for a book, saving it to their list, and managing their saved books by deleting one." src="./assets/images/placeholder.jpg"/>
</p>

Clicking the login/signup button on the main page will bring users to a login portal. The user can toggle the modal between a "sign up" or "login" option. Here they can either enter new credentials to sign up as a user in the signup section, or they can enter their already verfied credentials into the login section. To sign up, users must provide a username, a valid email address, and a password. To login, they only need to provide their email address and password for verification. Later, users can logout using the "logout" button that appears in the site's navigation.

[start from homepage, click login/signup, signup]

<p align="center">
<img alt="A demonstration gif showing the user signing up for the site, then logging out." src="./assets/images/placeholder.jpg"/> 
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
