# frozen_string_literal: true

source 'https://rubygems.org'

ruby '3.0.1'

gem 'rails', '~> 6.1.3'

gem 'bootsnap', '>= 1.4.4', require: false
gem 'composite_primary_keys'
gem 'listen'
gem 'pg', '~> 1.1'
gem 'puma', '~> 5.0'

gem 'aws-sdk-sns'
gem 'aws-sdk-sqs'
# Use Rack CORS for handling Cross-Origin Resource Sharing (CORS), making cross-origin AJAX possible
# gem 'rack-cors'

gem 'committee', '~> 4.4'
gem 'openapi_parser', '~> 1.0'

gem 'ddtrace'
gem 'faraday'
gem 'faraday_middleware'
gem 'oauth2'
gem 'redis'
gem 'shoryuken'
gem 'simple_xlsx_reader'

group :development, :test do
  gem 'pry', '~> 0.14.1'
  gem 'pry-rails'
  gem 'pry-remote'
end

group :test do
  gem 'committee-rails'
  gem 'factory_bot_rails'
  gem 'rspec-rails'
  gem 'shoulda'
  gem 'shoulda-matchers'
  gem 'simplecov', require: false
  gem 'simplecov_json_formatter', require: false
  gem 'webmock'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
