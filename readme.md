# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

- Install docker.
- Validate docker is running: `systemctl status docker` `docker -v` `docker-compose -v`
- Start containers. From within the root of this project run: `docker-compose up`
- Confirm frontend deployment: `http://localhost:3000/api/ping`
- Confirm database deployment: `http://localhost:3001/register`
