# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

gemspec

group :development, :test do
  gem 'appraisal'
  gem 'puma'
  gem 'sqlite3'
  gem 'actionpack', '~> 7.0.0'
  gem 'actionview', '~> 7.0.0'

  # Testing
  gem 'capybara'
  gem 'cuprite'
  gem 'rails-controller-testing'
  gem 'rspec_junit_formatter'
  gem 'rspec-rails'

  # Linters
  gem 'fasterer'
  gem 'rubocop'
  gem 'rubocop-packaging'
  gem 'rubocop-performance'
  gem 'rubocop-rails'
  gem 'rubocop-rspec'

  # Tools
  gem 'pry-rails'
end
