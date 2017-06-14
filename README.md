# README

This README would normally document whatever steps are necessary to get the
application up and running.
rails new toy_app --database=postgresql

Things you may want to cover:

* Ruby version
2.4.1

* System dependencies

* Configuration

* Database creation
set up Rails with Postgres : https://www.digitalocean.com/community/tutorials/how-to-setup-ruby-on-rails-with-postgres
Create a user ex rails_user and
Allow the user to create a database `ALTER USER rails_user CREATEDB;`
After filling config/database.yml
* Database initialization

rake db:setup

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...
