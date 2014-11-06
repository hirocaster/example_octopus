source 'https://rubygems.org'


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '4.1.7'
# Use mysql as the database for Active Record
gem 'mysql2'
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


gem "rails_config"
gem "whenever"
gem "kaminari"
gem "parallel"
gem "faraday"
gem "httpclient"
gem "dalli", require: "active_support/cache/dalli_store"
gem "activeadmin", github: "gregbell/active_admin"
gem "kakurenbo"
gem "nokogiri"
gem "ar-octopus"
group :deployment do
  gem "net-ssh", "2.7.0"
  gem "capistrano", "~> 3.2.0"
  gem "capistrano-rbenv", "~> 2.0"
  gem "capistrano-bundler", "~> 1.1.2"
  gem "capistrano-rails", "~> 1.1"
  gem "supply_drop", git: "git@github.com:thoward/supply_drop.git", branch: "cap_3"
  gem "puppet"
  gem "librarian-puppet"
end

group :development do
  gem "seed_dump"
end

group :development, :test do
  gem "rspec-rails"
  gem "spring-commands-rspec"
  gem "pry"
  gem "pry-coolline"
  gem "pry-rails"
  gem "hirb-unicode"
  gem "database_rewinder"
  gem "factory_girl_rails"
  gem "pry-byebug"
  gem "webmock"
  gem "vcr"
  gem "bullet"
  gem "bundler-auto-update"
  gem "metric_fu", git: "https://github.com/metricfu/metric_fu.git"
  gem "rubocop"
  gem "simplecov"
  gem "simplecov-rcov-text"
  gem "compass"
end
