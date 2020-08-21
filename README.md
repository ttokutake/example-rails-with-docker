# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

## Run Server

```bash
docker-compose up
```

## Run Server for Development

```bash
$ docker-compose -f docker-compose-dev.yml build
$ docker-compose -f docker-compose-dev.yml run -p 3000:3000 rails bash
> bundle install
> yarn
> bin/rails s -b 0.0.0.0
```
