source 'https://rubygems.org'
ruby '2.3.1'
#ruby-gemset=railstutorial_rails_4_0

gem 'rails', '4.2.10'
gem 'bootstrap-sass'
gem 'sprockets'
gem 'bcrypt'
gem 'faker'
gem 'will_paginate'
gem 'bootstrap-will_paginate'

group :development, :test do
	gem 'sqlite3'
	gem 'rspec-rails'
	#The following options lines are part of the advanced setup.
	#gem 'guard-rspec'
	#gem 'spork-rails'
	#gem 'guard-spork'
	#gem 'childprocess'
end

group :test do
	gem 'selenium-webdriver'
	gem 'capybara'
	gem 'factory_bot'
	gem 'cucumber-rails', :require => false
	gem 'database_cleaner', github: 'bmabey/database_cleaner'

 #Uncomment this line on OS X.
 #gem 'growl'

 #Uncomment these lines on Linux.
 gem 'libnotify'

 #Uncomment these lines on Windows.
 #gem 'rb-notifu'
 #gem 'wdm'
end

gem 'sass-rails'
gem 'uglifier'
gem 'coffee-rails', '4.0.1'
gem 'jquery-rails', '3.0.4'
gem 'turbolinks'
gem 'jbuilder', '1.0.2'
gem 'json', '1.8.6'
gem 'nokogiri'
gem 'multi_json'

group :development, :test do
	gem 'byebug'
end

group :development do
  gem 'web-console', '~> 2.0'
  gem 'spring'
end

group :doc do
  # bundle exec rake doc:rails generates the API under doc/api.
  gem 'sdoc', require: false
end

group :production do
	gem 'pg'
	gem 'rails_12factor', '0.0.2'
end
