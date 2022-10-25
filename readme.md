# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Create a directory and clone the repository to your local machine by running the following command inside the directory you just created.

`git clone https://github.com/ObelusFamily/Anythink-Market-k8ozt.git .`

2. Enter the project's root directory.

`cd <folder-name>`

3. Bring up the compose stack by running the following command.

`docker compose up`

4. When your containers are ready, check the backend container by clicking http://localhost:3000/api/ping

> You should see the following response.
> {"msg":"Pong! Seems like Everythink is working, great job!"}

5. Check the frontend container by creating a user on http://localhost:3001/register

> If you can create a user, your frontend and database containers are working properly.


