# Sportradar code challenge

## Description
This repository is created for convinience, so you can use docker-compose to build and start faster both the fronted and the backend side of the
code challenge at the same time. To do so, once you have cloned both repositories inside of this project, you should be able to run the following commands
  
  1. docker compose build
  2. docker compose up

And once they are finished, you will be able to go to "http://localhost:3000" to see the frontend widget. The environment variables are hardcoded in the docker-compose file but you should be able to change them if you need to, or export them from bash.