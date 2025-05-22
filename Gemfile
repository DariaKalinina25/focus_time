source "https://rubygems.org"

gem "rails", "~> 8.0.2"
gem "propshaft"
gem "pg", "~> 1.1"
gem "puma", ">= 5.0"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"
gem "tzinfo-data", platforms: %i[ windows jruby ]
gem "solid_cache"
gem "solid_queue"
gem "solid_cable"
gem "bootsnap", require: false
gem "kamal", require: false
gem "thruster", require: false

group :development, :test do
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"
  gem "brakeman", require: false
  gem "rubocop-rails-omakase", require: false
  gem "dotenv-rails", "~> 3.1", ">= 3.1.8"

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
  gem "web-console"
end
