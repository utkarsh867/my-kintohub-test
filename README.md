[![Build Status](https://travis-ci.org/utkarsh867/my-kintohub-test.svg?branch=master)](https://travis-ci.org/utkarsh867/my-kintohub-test)
# Submission for the test

## Dependencies for deployment
* `docker` - Install docker and make sure that the deamon is running
* `docker-compose` - Install docker-compose for the command-line.

## How to run the deployment

Clone this github repo   
`git clone https://github.com/utkarsh867/my-kintohub-test.git`   

Then move into the repo directory   
`cd my-kintohub-test`   

Run docker-compose   
`docker-compose up`

## How to test on your local machine

The applications can be tested locally by running each of them separately   

Move into the directory   
`cd <microservice>`   

Install all the dependencies   
`npm install`   

Start the deployment locally   
`PORT=<PORT-NO> npm start`   

## How to run the development environment
Move into the directory   
`cd <microservice>`   

Install all the dependencies   
`npm install`   

Start the deployment locally   
`PORT=<PORT-NO> npm run dev`   

#### Note that environment variable `JWTSECRET` must be defined when running the application during development and tests.