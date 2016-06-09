== README

This README would normally document whatever steps are necessary to get the
application up and running.

* Ruby version 

ruby 2.3.0p0 (2015-12-25 revision 53290) 

* System dependencies

[x86_64-linux]

rails server -b $IP -p $PORT

gem 'rspec-rails', '~> 3.4'
gem 'capybara'
gem 'factory_girl_rails'

gem 'simple_form'
rails generate simple_form:install

rpm -Uvh ImageMagick-7.0.1-6.i386.rpm
gem "paperclip", "~> 5.0.0.beta1"
bin/rails g paperclip post image

gem "factory_girl_rails"

gem 'devise'
rails g devise:install

wget -O- https://toolbelt.heroku.com/install-ubuntu.sh | sh

heroku run rake db:migrate



