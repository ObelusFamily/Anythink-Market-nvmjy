# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Install docker from [here](https://docs.docker.com/get-docker/)
2. Verify your installation by running `docker --version` and `docker-compose -v`
3. Run `docker-compose up` to load the frontend and the backend
4. Test the backend by visiting http://localhost:3000/api/ping in your browser
5. Check if the frontend is connected to the backend by visiting http://localhost:3001/register and registering with dummy credentials
