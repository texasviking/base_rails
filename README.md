Base Rails Application
======================

Includes 
--------
- Ruby 2.0.0 p353
- Rails 4.1.1
- Bootstrap 2.3.2 (via https://github.com/seyhunak/twitter-bootstrap-rails)

Install Steps
-------------
1. bundle install
1. rails s

Creating A Model
----------------
1. rails g scaffold Post title:string description:text
1. rake db:migrate
1. rails g bootstrap:themed Posts
