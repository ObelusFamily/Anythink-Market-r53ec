# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. [Create your own codespace](https://github.com/codespaces/new?hide_repo_select=true&ref=main&repo=557826342).
    (No need to change anything in the default options, just click on the Create codespace button and wait for it to boot)
2. After codespace is ready, you can  run docker-compose up in your codespace's terminal to load Anythink's backend and frontend.
    Once docker-compose finishes loading up, the backend should be running and able to connect to the database.
3. Test it by pointing your browser to https://obelusfamily-anythink-market-r53ec-9v97qg4qpvj39p96-3000.githubpreview.dev/api/ping
4. Verify Frontend and Backemd are connected by creating a new user in the environment, by browesing to https://obelusfamily-anythink-market-r53ec-9v97qg4qpvj39p96-3001.githubpreview.dev/register
