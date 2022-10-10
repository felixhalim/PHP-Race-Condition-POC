# PHP-Race-Condition-POC
This repo contains a PHP Race Condition POC that simulates a Race Condition seen in Starbucks gift cards in 2015.

# Setup:
**Note*** May not work on M1 Mac or other ARM-based OSes. If you find a solution, please feel free to suggest a commit!
1. install [Docker](https://docs.docker.com/get-docker/).
2. in the directory with the `docker-compose.yml` file, run the command `docker-compose up`.
3. The vulnerable web server is now running on `localhost:6969`.
4. There should be '2 gift cards with $500 each'. Your goal is to increase the sum of the total value.

# Resetting the container:
1. Open a seperate terminal also in the directory with the `docker-compose.yml` file and run the command `docker-compose down -v`.
