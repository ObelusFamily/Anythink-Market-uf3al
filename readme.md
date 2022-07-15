# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

Run `docker-compose up` from the project root directory to load Anythink's backend and frontend. If Docker is working correctly, the backend should be running and able to connect to your local database.
We can test this by pointing your browser to `http://localhost:3000/api/ping`. All you need to do now is run the frontend and make sure it’s connected to the backend. Try to open the user registration page and create a test user. Here’s the link: http://localhost:3001/register. Now that you have everything set up, just make sure that you run all scripts on one of the containers you created using the docker-compose up command.  Also, you can use docker exec to run commands on a running container.
