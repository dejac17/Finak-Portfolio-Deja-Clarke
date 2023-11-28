# Project #1: Spongebob Recipe Book

## High-level Project Overview

- The Spongebob Recipe Book was created to help Spongebob store his secret recipes from Plankton. The users of the Spongebob Recipe Book are primarily Spongebob himself and anyone else he trusts with his secret recipes. The Recipe Book serves as a convenient and secure way for Spongebob to organize and access his secret recipes whenever he needs them. It eliminates the risk of Plankton stealing or tampering with them due to authorization.

- The inspiration behind creating this project stems from Spongebob's desire to protect his secret recipes from Plankton's constant attempts to steal them. The ost important feature is the authorization created using 0Auth2

### Situation

- This recipe book allows user to login, and be granted the ability to create, read, update, and delete a recipe. To gain access a user must be authorized by login in. Initially the only user that can login is Spongebob, Spongebob also has the access to add other authorized users.

### Task

- Create a Recipes model that will have the structure for each of the recipes
- Create a server and routes that allow users to login and make changes to the recipe book.
- Create a databse that will store the recipes and allow access when needed

### Action

- Backend
  - We created a Recipes model in the `models` file that includes the name of the recipe, the ingredients needed, and the approximate prep time
  - We created the get, post, put, and delete routes in the `routes` folder
  - Created functions that login and authorize users in the `server.js` file
  - Created seed data to test the logic in our function in the `seed.js` file
- Security
  - Implemented authorization using oauth2 that allows Spongebob to login

### Result

[Final Project Video Presentation](https://youtu.be/EvvSNexul6g?si=AMTOg7yzmQDH0Ve)

- The end result was a back end project that was fully tested using postman

## Technologies

- OAuth2
- Node.js
- Sequelize
- Express
- JWT
- Html, Css
- Postman for testing routes

## Competencies

### JF 3.7

Can Implement authentication and authorization to an API

- Built an api and added authorization for logged in users using an /authorized endpoint. Also added authorization where only the admin user "Spongebob" could give users access to the api.
- This allowed be to learn more about how to create secure sign in pages, while also learning about jwt and OAuth

### JF 6.5

Works collaboratively with a wide range of people in different roles, internally and externally, with a positive attitude to inclusion & diversity

- I worked in a group of four, collaborating on various parts of this project. We created a board to manage our project tiers, and assigned each member of our team different tickets for this project.
- I worked together with my team to solve any technical issues that we encountered. This helped me get real world experience working in a collaborative environment on a team.
