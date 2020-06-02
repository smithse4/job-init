# Job Init

## Table of Contents
* [Overview](#Overview)  
* [User Story](#user-Story)   
* [Screenshots](#Screenshots)  
* [How to Use](#How-to-Use)  
* [Links](#Links)
* [Credits](#Credits) 
* [License](#License) 

### Questions? Email me [here.](mailto:smithse4@gmail.com)

## Overview

This application is designed to aggregate job listings specifically for web developers. The user sets their skills when signing up for the web site and it automatically aggregates job listings for that user based upon what they selected. It was built with the MERN stack.

The front end was built using React and can be found in the client folder. The database used for user data is Mongo used with Mongoose. The schema for the database is in the models folder. Node JS and Express are used to route between front end and database. 

Adzuna API was used to pull in aggregated job listings.

## User Story

As a user 
I WANT to input my skills and job preferences 
SO THAT I can receive personalized jobs listings.

## Screenshots

Home Screenshot

![Home Screenshot](/client/src/img/home.jpeg)

Login Screenshot

![Login Screenshot](/client/src/img/login.jpeg)

Sign up Screenshot

![Sign up Screenshot](/client/src/img/signUp.jpeg)

User Dashboard Screenshot

![User Dashboard Screenshot](/client/src/img/dashboard.jpeg)


## How to Use
1. Open the page and either login if you already have an account or sign up if you are a new user,

2. To sign up, simply click sign up button in home page and this will take you to sign up page so that you are able to create an account. Type in first name, last name, email address, password and location. Choose the appropriate skills and click "Sign Up."

3. Once you create an account, you will automatically redirected to your dashboard and job listings will be populated based on the skills chosen on the sign up page.

## Installing

To run the app locally, you will first need to git clone the repository to your local machine.

* Cd into repository
* Install dependencies by running 'npm install'
* Start app by running 'npm run dev'

## Links

* [Deployed app](https://job-int.herokuapp.com/)

* [Github Repo](https://github.com/smithse4/job-init)

## Credits

SamSherrill, smithse4, jguerra21, fmiusov


