# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.1'

gem 'rails', '~> 6.0.0.rc1'

gem 'aws-sdk-s3', '~> 1.8.2'
gem 'bootsnap', '>= 1.4.2', require: false
gem 'bootstrap'
gem 'bootstrap_form'
gem 'clearance'
gem 'dotenv-rails', groups: %i[development test]
gem 'haml'
gem 'jbuilder', '~> 2.5'
gem 'jquery-rails'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 4.3'
gem 'sass-rails', '~> 5'
gem 'turbolinks', '~> 5'
gem 'webpacker', '~> 4.0'

group :development, :test do
  gem 'factory_bot_rails'
  gem 'pry-rails'
  gem 'rspec-rails'
end

group :development do
  gem 'fasterer', require: false
  gem 'haml-lint', require: false
  gem 'haml-rails'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'reek'
  gem 'rubocop-rails'
  gem 'rubycritic'
  gem 'scss_lint'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'web-console', '>= 3.3.0'
end

group :test do
  gem 'apparition', github: 'twalpole/apparition', ref: 'c6ef18f'
  gem 'capybara'
  gem 'rspec_junit_formatter'
  gem 'simplecov'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
