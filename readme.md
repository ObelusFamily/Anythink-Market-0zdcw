# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

**[TODO 05/01/2018 @vanessa-cooper]:** _It's been a while since anyone ran a fresh copy of this repo. I think it's worth documenting the steps needed to install and run the repo on a new machine?_
1. Install Docker on your machine
2. Verify docker is working with the following commamnds in a terminal:
    _docker -v 
    _docker-compose -v
3. Navigate to where you cloned the project repository in the terminal
4. Run _docker-compose up_ to load the backend and frontend
5. In a browser, go to http://localhost:3000/api/ping
6. Check the frontend at http://localhost:3001/register
