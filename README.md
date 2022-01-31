# My personal web portfolio

Dockerized laravel app for web portfolio.
using LEMP, Adminer as db web interface

### Softwate Requirements

-   Docker

### Configuration

1. Clone the portfolio repository to your local machine.

2. Create a .env file based off .env.example

3. Start docker engine

4. Build containers

    - docker-compose build

5. Bring up containers in detached mode

    - docker-compose up -d

6. SSH into the app container

    - docker exec -it -u ubuntu portfolio_app /bin/bash

7. Run the following commands

    - composer install
    - php artisan key:generate
    - npm install
    - npm run watch / npm run dev

8. Visit the following urls to ensure everything is correctly setup:

    - **[Laravel Server](http://localhost:8088)**
    - **[Adminer](http://localhost:8089)**
