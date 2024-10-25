# Project_10
Team 10 Congressional Invesment Tracker


## Description
This project provides a webpage allowing users to see what their elected officials are up to in the world of stocks. Users are able to create accounts and store which officials they would like to keep track of, as well as mark down their favorites and who to watch. 

As we know, our elected officials are very good at trading stocks, so why not learn from the best and have access to all of their trades. This is the perfect project for those interested in the world of stocks and looking to get a leg up, as well as for those looking to monitor how money is changing hands in Washington. 


## Architecture Overview
__Frontend:__
- Frontend development for our project will be done in Javascript, making use of libraries such as react and node.js
- Users will be able to interact with our project through a webpage

__Backend:__
- Backend development for our project will be done in python
- Our Python backend will utilize Flask to listen to our client's requests, process them, and retrieve appropriate data from our database

__Database:__
- For our database we will be using MySQL
- More specifically, we will be using Docker to containerize our project.
    - This includes a Docker container running a MySQL image 
- These Docker containers will be up and running on virtual machines for easy access any time

## Usage
*not yet implemented*

Users will be able to open the webpage for our app with a simple [url](http://localhost:3000). 

- From here, they will be prompted to log in or create an account. 
- Once logged in, users will be able to 
    - favorite politicians, 
    - select which politician's trades they would like to see, 
    - and see a timeline of how a portfolio they previously marked has changed.
- Users will then be able to log out with the click of a button

## Visuals
*eg screenshots or GIFS*

## Roadmap
- [X] Have a MySQL DB up and running in a docker container environment
- [X] Able to query this database via a python file
- [X] Have an existing python backend
- [X] Have an existing js frontend
- [ ] Decide on an API to use to retrieve congressional stock trading data
- [ ] Have our backend be able to listen to the frontend
- [ ] Implement a walking skeleton (full connection from frontend to DB)

## Project status
Currently in progress (*check = in progress or completed*)
- [X] Sprint 0
- [ ] Sprint 1
- [ ] Sprint 2
- [ ] Sprint 3

## Authors
Aidan Carrig, Anish Damani, Ritvik Gudlavaletti, Garett Hetchler, Weicong Liang, Seyeong Oh

## License
*For open source projects, say how it is licensed*
