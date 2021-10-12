source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.5'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 6.0.0'
# Use postgresql as the database for Active Record
gem 'pg', '>= 0.18', '< 2.0'
# Use Puma as the app server
gem 'puma', '~> 4.3'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false

# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
gem 'rack-cors', '~> 1.0', '>= 1.0.3'

# Flexible authentication solution for Rails with Warden.
gem 'devise', '~> 4.7', '>= 4.7.1'
# Para uso com aplicativos de página única do lado do cliente, como o venerável https://github.com/lynndylanhurley/ng-token-auth.
gem 'devise_token_auth', '~> 1.1', '>= 1.1.3'
# ActiveModel::Serializers allows you to generate your JSON in an object-oriented and convention-driven manner.
gem 'active_model_serializers', '~> 0.10.10'
# Centralization of locale data collection for Ruby on Rails.
gem 'rails-i18n', '~> 6.0'
# Simple HTTP and REST client for Ruby, inspired by microframework syntax for specifying actions.
gem 'rest-client', '~> 2.1'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'rspec-rails', '~> 3.9'
  # factory_bot is a fixtures replacement with a straightforward definition syntax, support for multiple build strategies (saved instances, unsaved instances, attribute hashes, and stubbed objects), and support for multiple factories for the same class (user, admin_user, and so on), including factory inheritance.
  gem 'factory_bot_rails', '~> 5.1', '>= 5.1.1'
  # A library for generating fake data such as names, addresses, and phone numbers.
  gem 'faker', '~> 2.6'
  # An IRB alternative and runtime developer console
  gem 'pry-rails', '~> 0.3.9'
end

group :development do
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring', '~> 2.1'
  gem 'spring-watcher-listen', '~> 2.0', '>= 2.0.1'
  # This gem implements the rspec command for Spring.
  gem 'spring-commands-rspec', '~> 1.0', '>= 1.0.4'
  # Rename your Rails application using a single command.
  gem 'rename', '~> 1.0', '>= 1.0.6'
end

group :test do
  # Strategies for cleaning databases in Ruby. Can be used to ensure a clean state for testing.
  gem 'database_cleaner', '~> 1.7'
  # Shoulda Matchers provides RSpec- and Minitest-compatible one-liners that test common Rails functionality.
  gem 'shoulda-matchers', '~> 4.1', '>= 4.1.2'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
