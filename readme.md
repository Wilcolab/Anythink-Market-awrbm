# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Clone the repo
2. Install Docker locally
   1. Confirm Docker is installed with `docker -v` or `docker compose -v`
3. Run `docker-compose up` from the project root directory to load Anythink's backend and frontend.
    1. Confirm by pinging `http://localhost:3000/api/ping`
4. Access the registration page with `http://localhost:3001/register`
