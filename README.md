Base Rails Application
======================

Requirements
------------
- Homebrew
  ruby -e "$(curl -fsSL https://raw.github.com/Homebrew/homebrew/go/install)"
- Rbenv and ruby-build
  https://github.com/sstephenson/rbenv#homebrew-on-mac-os-x
- Ruby 2.0.0 p353
  rbenv install 2.0.0-p353

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
