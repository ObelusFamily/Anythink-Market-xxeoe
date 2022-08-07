# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

```
# Check Docker is installed
docker --version
docker-compose -v

# Load Anythink's backend and frontend images
docker-compose up
```

Check the app is running by visiting http://localhost:3000/api/ping.
To access the app front end, visit http://localhost:3001/register.
