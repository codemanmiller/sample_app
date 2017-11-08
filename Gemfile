source 'https://rubygems.org'
ruby '2.3.1'
#ruby-gemset=railstutorial_rails_4_0

gem 'rails', '4.2.10'

group :development, :test do
	gem 'sqlite3'
	gem 'rspec-rails'
end

group :test do
	gem 'selenium-webdriver'
	gem 'capybara'
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
	gem 'pg', '0.15.1'
	gem 'rails_12factor', '0.0.2'
end
