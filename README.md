# Almabetter - Capstone project ( 2nd ) - BookMyShow

This is a backend capston project given by almabetter in this project we created bookmyshow website this project have vary simple UI and this website is very easy to use ( userfriendly ) and also a work in any devices ( Responsiveness ) .

# Deployment Links

click on the line to see the project

Frontend on netlify.com
bookmyshows-frontend.netlify.app

Backend on cyclic.sh

https://ruby-puzzled-kitten.cyclic.app/api/booking

# Installation

open this project on you local IDE and in the terminal do this commands one by one

for Frotend bash cd frontend
npm install

npm start

for backend bash cd backend
npm install

npm start

This will start you frontend part in http://localhost:3000 and backend part running in http://localhost:8080

# How to use

Click on this link for using the website

bookmyshows-frontend.netlify.app

First select movie you like
select time schedule
select seats
click on Book show button the confirmation pop window will open close this and see right side on the screen the previous movie ticket will show
Tech Stack
Frontend: React js,

backend: Node js, Express js ,

database: Mongodb

This is a MERN stack project

Environment Variables
To run this project, you will need to add the following environment variables to your .env file

Note : your mongodb clustur connect key

API_KEY

MONGOURI : mongodb+srv://user_name:@cluster0.adfedxd.mongodb.net/<batabase_name>?retryWrites=true&w=majority

# API Documentation

Base URL
https://ruby-puzzled-kitten.cyclic.app/api

Booking
get the booking

GET /booking
Returns a list of last booking stored in the database in JSON format.

post /booking
Parameter Type Description
movie string Required. your selected movie
slots string Required. your selected time
Seats number Required. no of seats you have seleacted
Returns the newly created booking in JSON format

# Support

For support, email

shubhamaagawane@gmail.com

# project created with

1] Shubham Aagawane,
2] Rushikesh Waghmare,
3] Tushar sonwane
