# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?

Step 1: clone this repo on your local machine using command
git clone https://github.com/ObelusFamily/Anythink-Market-c8cw3

Step 2: cd Anything-Market-c8cw3

step 3: verify docker is installed on you local machine using command
docker -V

Step 4: run docker-compose up from the project root directory to load Anythink's backend and frontend

Step 5: If Docker is working correctly, the backend should be running and able to connect to your local database.
Test this by pointing your browser to http://localhost:3000/api/ping

Step 6: If everything is working properly, you’ll be able to create a new user on http://localhost:3001/register

