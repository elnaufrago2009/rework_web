source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.1'
# Use sqlite3 as the database for Active Record
gem 'sqlite3'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 4.0.3'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# Use CoffeeScript for .js.coffee assets and views
gem 'coffee-rails', '~> 4.0.0'
# See https://github.com/sstephenson/execjs#readme for more supported runtimes
# gem 'therubyracer',  platforms: :ruby

# Use jquery as the JavaScript library
gem 'jquery-rails'
# Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
gem 'turbolinks'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.0'
# bundle exec rake doc:rails generates the API under doc/api.
gem 'sdoc', '~> 0.4.0',          group: :doc

# Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
gem 'spring',        group: :development

# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use unicorn as the app server
# gem 'unicorn'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Use debugger
# gem 'debugger', group: [:development, :test]

gem 'unicorn'

# Use Capistrano for deployment
gem 'capistrano', '~> 3.2.1', require: false, group: :development
group :development do
  gem 'capistrano3-unicorn'
  gem 'capistrano-rvm',   '~> 0.1.1', require: false
  gem 'capistrano-rails',   '~> 1.1.1', require: false
  gem 'capistrano-bundler', '~> 1.1.2', require: false
end

gem 'nested_form'
gem 'friendly_id', '~> 5.0.0'
gem 'globalize', '~> 4.0.1'
gem 'scaffold-bootstrap3'
gem 'bootstrap-sass', '~> 3.1.1.1'
gem 'compass-rails', group: :assets
gem 'rails_layout', group: :development
gem 'haml'
gem 'inherited_resources'
gem 'devise'
gem 'mini_magick'
gem 'page_title_helper'
gem 'execjs'
gem 'therubyracer'

group :test, :development do
  gem 'rspec-rails', '~> 2.14.2'
  gem 'factory_girl_rails', '~> 4.4.1'
end

group :test do
  gem 'capybara', '~> 2.2.1'
  gem 'launchy', '~> 2.4.2'
  gem 'cucumber-rails', '~> 1.4.1', :require => false
  gem 'selenium-webdriver', '~> 2.42.0'
  # database_cleaner is not required, but highly recommended
  gem 'database_cleaner', '~> 1.2.0'
  gem 'faker', '~> 1.3.0'
end