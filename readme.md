# Welcome to the Anythink Market repo

To start the app use Docker. It will start both frontend and backend, including all the relevant dependencies, and the db.

Please find more info about each part in the relevant Readme file ([frontend](frontend/readme.md) and [backend](backend/README.md)).

## Development

When implementing a new feature or fixing a bug, please create a new pull request against `main` from a feature/bug branch and add `@vanessa-cooper` as reviewer.

## First setup

1. Download and install [Docker](https://docs.docker.com/get-docker/).
2. Run the following commands in the terminal to verify Docker is ready:
   
    ```
    docker -v
    docker-compose -v
    ``` 

3. Run this command to start Docker:
   
   ```
   docker-compose up
   ```
   
4. Check if the everthing is working [here](http://localhost:3000/api/ping).
    
5. If everything is working properly, create a [new user](http://localhost:3001/register).