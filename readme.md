# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Clone this repository on your computer.
2. Create your own [codespace](https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=557264927) by clicking on the button shown once the page opens
3. Wait until Visual Studio code (VSC) opens in your browser
4. execute `docker-compose up` in terminal of VSC

To access the frontend or backend, follow the provided links:
* [Backend](https://obelusfamily-anythink-market-fqksi-q764qv4rq97c4xw6-3000.githubpreview.dev/api/ping)
* [Frontend](https://obelusfamily-anythink-market-fqksi-q764qv4rq97c4xw6-3001.githubpreview.dev/register)

You can use ```docker exec``` to run commands on a running container.
