# Cargo Owners - Master Repository

This repository is the main access point for both the Frontend and Backend of this project.

## Cargo Owners | Frontend

The frontend consists of the following:

1. ReactJS - Used to build web application
2. NodeJS - Development server
3. TailwindCSS - For pre-built styles
4. React-Bootstrap - For pre-built components
5. Netlify - CI/CD Integration and Hosting
6. Figma - For mock-up designs | [Link](https://www.figma.com/community/file/1042466647808574080/Cargo-Owners)
7. Production URI - [Link](https://cargo-owners-fe.netlify.app/)

## Cargo Owners | Backend

The backend consists of the following:

1. ExpressJS - Used to build Web API
2. MongoDB - Utilized for storing User, Transporter and Averages Data
3. Heroku - CI/CD Integration and Hosting
4. Production URI - [Link](https://cargo-owners-api.herokuapp.com/)

## Retrospectives & Reasoning

1. Don't implement a separate Backend build and instead integrate the Backend functionality into the Frontend directly
2. The initial idea was to implement a Frontend that mainly managed the visible aspect of the web application and would later integrate into the Web API. The Backend would mainly handle the login authentication, which is setup for both reaching the Dashboard page and being able to access the database functionality via an authorized session. The database handler on the Backend would handle all query & mutation requests to the database and would return the data via the Web API.

## Repositories

* Cargo Owners [Frontend](https://github.com/krampus-nuggets/cargo-owners-fe)
* Cargo Owners [Backend](https://github.com/krampus-nuggets/cargo-owners-be)