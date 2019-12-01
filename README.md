# Scraper

Scraper is a a web app that lets users view and leave comments on the latest news from the New York Times.

## Getting started
$ git clone
$ cd scraper/
$ npm install
```
### deploying to Heroku
```shell
$ heroku login
$ Email: <enter email>
$ Password: <password>
$ heroku create <enter app name>
$ heroku addons:create mongolab
$ git push heroku master

