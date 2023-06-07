# RSsSetup

Aim of this repository is to help anyone start their own Self-Hosted RSS aggregator with minimal setup.

# Configurations Available

- [Basic](/Basic) : Most Basic setup with [FreshRss](https://github.com/FreshRSS/FreshRSS) & [Watchtower](https://github.com/containrrr/watchtower)
- [FullText](/FullText) : Basic along with [fivefilters-full-text-rss](https://github.com/heussd/fivefilters-full-text-rss-docker)
- [RssHub](/RssHub) : FullText along with [RssHub](https://github.com/DIYgod/RSSHub)

# Requirements

Docker installed on the system

# How to Use

## Local Windows/Linux Setup

1. Clone each file of your favorite Configuration locally.
2. Make sure you have docker and docker compose is installed.
3. Change the environment variables **TZ** in the [docker-compose file](./docker-compose.yml) to your country value.
4. Run `docker compose up`
5. Go to http://localhost
6. Do the initial one time FreshRss setup.
7. Don't change Database Configuration for FreshRss in setup. Let it be the default "SQLite"
8. Check *Respective Configuration Folder for additional setup*.
9. Refer [FreshRss](https://github.com/FreshRSS/FreshRSS) [first steps documentation](https://freshrss.github.io/FreshRSS/en/users/02_First_steps.html) for more.
10. ***CAUTION*** To Delete all Data and containers run `docker compose down -v`

## CLI Setup
### Oracle Linux

### Ubuntu Linux

# Contributing

If you find a bug or would like to suggest an enhancement, please open an issue on this repository. Pull requests are most welcome!
