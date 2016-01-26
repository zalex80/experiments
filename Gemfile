source 'https://rubygems.org'
ruby File.read('.ruby-version').gsub(/[[:space:]]+/, '')

gem 'rails', '~> 4.2'

# ENV secrets
gem 'dotenv-rails', require: 'dotenv/rails-now'

# Database adapters
gem 'sqlite3'

# DSLs
gem 'slim-rails'
gem 'sass-rails'
gem 'coffee-rails'
gem 'jbuilder'

# Vendor assets and frameworks
gem 'bootstrap-sass'
gem 'jquery-rails'

# Asset related tools
gem 'uglifier'
gem 'therubyracer', platforms: :ruby

# Service provider tools
gem 'aws-sdk'

# Core extensions
gem 'awesome_print', require: false

# Deployment tools
gem 'capistrano-rails', group: :development

group :production do
  gem 'unicorn'
end

group :development do
  gem 'spring'
  gem 'byebug'
  gem 'web-console'
end

group :development, :test do
  gem 'rspec-rails'
  gem 'quiet_assets'
end
