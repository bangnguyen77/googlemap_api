# GOOGLE MAP API PRACTICE
#### By Bang Nguyen

## Description
This app allows visitors to create new users with addresses shown on the map.
And it lets users send text messages to their friends!

## General Setup Instructions
* Clone this repository
* Install gems by running command `$ bundle` in the terminal
* Open another terminal tab and type `postgres` to start PostgreSQL database
* Return to first terminal tab and run `rails db:create` to create the databases
* Run `rails db:migrate db:test:prepare` to create tables
* Run `rails db:seed` to seed the database
* Launch the Rails server by running command `$ rails s` in the terminal
* Launch site by visiting localhost:3000 in browser
* For texting from the app, Twilio account sid and auth token are needed


## User Stories
As a user I want to:
* As a user, I want to write, edit and delete a new user and the user's location is shown on the map.

## Tech Used

* Ruby on Rails (v. 5.0.0.1)
* Google Map API
* Active Record
* PostgreSQL
* Bootstrap/SCSS

### License

This software is licensed under the MIT license.

Copyright (c) 2016 * Bang Nguyen *
