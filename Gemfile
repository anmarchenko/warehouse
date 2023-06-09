# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.3', '>= 6.0.3.2'
# Use sqlite3 as the database for Active Record
gem 'sqlite3', '~> 1.4'
# Use Puma as the app server
gem 'puma', '~> 4.1'
# Use SCSS for stylesheets
gem 'sass-rails', '>= 6'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 4.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.7'
gem "blueprinter", "~> 0.25.0"
gem "devise", "~> 4.7.2"
gem "jwt", "~> 2.2"
gem 'dry-validation'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use Active Model has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Active Storage variant
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'listen', '~> 3.2'
  gem 'web-console', '>= 3.3.0'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of web drivers to run system tests with browsers
  gem 'webdrivers'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]

group :development, :test do
  gem 'bullet', '~> 6.1'
  gem 'codecov', '~> 0.1.19', require: false
  gem 'database_cleaner', '~> 1.8'
  gem 'database_consistency', '~> 0.8.4', require: false
  gem 'factory_bot_rails', '~> 6.1'
  gem 'faker', '~> 2.13'
  gem 'guard-rspec', '~> 4.7'
  gem 'pry-byebug', '~> 3.9.0'
  gem 'pry-rails', '~> 0.3.9'
  gem 'rspec-json_expectations', '~> 2.2'
  gem 'rspec-rails', '~> 4.0'
  gem 'rspec_junit_formatter', '~> 0.4.1', require: false
  gem 'rubocop-rspec-focused', '~> 1.0', require: false
  gem 'seed-fu', '~> 2.3'
  gem 'shoulda-matchers', '~> 4.3'
  gem 'simplecov', '~> 0.18.5', require: false
  gem 'simplecov-lcov', '~> 0.8.0', require: false
  gem 'spring', '~> 2.1.0'
  gem 'spring-commands-rspec', '~> 1.0'
  gem 'spring-commands-rubocop', '~> 0.2.0'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'standard', '~> 0.4.7', require: false
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
end
