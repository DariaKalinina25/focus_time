# frozen_string_literal: true

source 'https://rubygems.org'

gem 'bootsnap', require: false
gem 'importmap-rails'
gem 'jbuilder'
gem 'kamal', require: false
gem 'pg', '~> 1.1'
gem 'propshaft'
gem 'puma', '>= 5.0'
gem 'rails', '~> 8.0.2'
gem 'slim-rails', '~> 3.7'
gem 'solid_cable'
gem 'solid_cache'
gem 'solid_queue'
gem 'stimulus-rails'
gem 'thruster', require: false
gem 'turbo-rails'
gem 'tzinfo-data', platforms: %i[windows jruby]

group :development, :test do
  gem 'brakeman', require: false
  gem 'debug', platforms: %i[mri windows], require: 'debug/prelude'
  gem 'dotenv-rails', '~> 3.1', '>= 3.1.8'

  # Code quality
  gem 'rubocop', '~> 1.75', '>= 1.75.7', require: false
  gem 'rubocop-capybara', '~> 2.22', '>= 2.22.1', require: false
  gem 'rubocop-factory_bot', '~> 2.27', '>= 2.27.1', require: false
  gem 'rubocop-performance', '~> 1.25', require: false
  gem 'rubocop-rails', '~> 2.32', require: false
  gem 'rubocop-rspec', '~> 3.6', require: false
  gem 'rubocop-rspec_rails', '~> 2.31', require: false
  gem 'rubocop-slim', '~> 0.3.0', require: false
  gem 'slim_lint', '~> 0.33.0', require: false

  # Testing
  gem 'capybara', '~> 3.40'
  gem 'cuprite', '~> 0.17'
  gem 'database_cleaner-active_record', '~> 2.2', '>= 2.2.1'
  gem 'factory_bot_rails', '~> 6.4', '>= 6.4.4'
  gem 'rspec-rails', '~> 8.0'
  gem 'shoulda-matchers', '~> 6.5'
  gem 'test-prof', '~> 1.4', '>= 1.4.4'
end

group :development do
  gem 'web-console'
end
