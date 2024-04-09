# Docker App

This is a full stack **to do list** react app that has containerized with docker.

## About this Web Application 
This is a **To Do List** react web application. Users can add items, remove items, reorder items according to their needs in the app. 

| **Category**                 | **Technology/Tool**                                     |
|------------------------------|---------------------------------------------------------|
| **Programming Language**     | JavaScript (Node.js)                                           |
| **Database**                 | MongoDB                                            |
| **Containersation**           | Docker |

## About this repository

This repository contains 3 main directories named - frontend, backend, env

## Each Directory in detail 
1. Frontend 
    - Contains the entire `React` frontend code
    - Entry file for the React code is in the `src` directory named `index.js`
    - The `Dockerfile` contains all the docker commands needed to containerize the application
2. Backend
   
    - Contains the entire backend of the code and connects the frontend of the react app with `mongodb` database in the backend
    - Displays logs for the backend that can be accessed in the `logs` directory
    - The `Dockerfile` contains all the docker commands needed to containerize the application
3. Env
    > [!WARNING]  
    > This repository is only for demo purposes. This repository should **ALWAYS** be included the .gitignore file

    - This contains the repository env files with confidentail information like id and password

## Running the application 
  1. Clone the reposiotry in your workspace
  2. Open terminal in the same directory as the docker-compose directory
  3. Run command       `docker compose up` in the opened terminal
  4. Open your browser to `http://localhost:3000/`
