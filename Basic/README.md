# Basic RSsSetup

## Local Windows/Linux Setup

1. Clone each file locally.
2. Make sure you have docker and docker compose is installed.
3. Change the environment variables **TZ** in the [docker-compose file](./docker-compose.yml) to your country value.
4. Run `docker compose up`
5. Go to http://localhost
6. Do the initial one time FreshRss setup.
7. Don't change Database Configuration for FreshRss in setup. Let it be the default "SQLite"
8. Refer [FreshRss](https://github.com/FreshRSS/FreshRSS) [first steps documentation](https://freshrss.github.io/FreshRSS/en/users/02_First_steps.html) for more.
9. ***CAUTION*** To Delete all Data and containers run `docker compose down -v`

## Cloud Setup in AWS

## Cloud Setup in Oracle



