# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
1) First - Install Docker

2) Once you've set Docker up, verify that docker is ready by running these commands in your terminal:
 'docker -v' and 'docker-compose -v'
 
3) Next, run 'docker-compose up' from the project's root directory to load Anythink's Backend and Frontend

4) Once your files have loaded, to verify Docker is working correctly, the Backend should be running and able to connect to your local database. Test this by pointing your browser to http://localhost:3000/api/ping

5) Next up is to check the Frontend has loaded correctly, and make sure it's connected to the backend.  If it is working properly, you'll be able to create a new user on http://localhost:3001/register

If the Frontend and Backend are running correctly, congratulations! 
