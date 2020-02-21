source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.2'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.2'
# Use postgresql as the database for Active Record
gem 'pg', '>= 0.18', '< 2.0'
# Use Puma as the app server
gem 'puma', '~> 3.11'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'mini_racer', platforms: :ruby

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
# gem 'turbolinks', '~> 5'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 4.0'
# Use ActiveModel has_secure_password
gem 'bcrypt', '~> 3.1.7'

# Use ActiveStorage variant
# gem 'mini_magick', '~> 4.8'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false

gem 'bootstrap-sass', '~> 3.3.6'
gem 'bootstrap-will_paginate'
gem 'bootstrap-datetimepicker-rails', github: 'shah743/bootstrap-datetimepicker-rails'
gem 'bootstrap-datepicker-rails'
gem 'jquery-rails'
gem 'fancybox-rails'
gem 'jquery-ui-rails'
# gem 'jquery-turbolinks'
gem 'font-awesome-rails'
gem 'kaminari'
gem 'will_paginate'
gem 'ransack'

gem 'puma_worker_killer'
gem 'nprogress-rails'
gem 'initialjs-rails', github: 'shah743/initialjs-rails'
gem 'yaml_db'
gem 'httparty'
gem 'geokit-rails', github: 'geokit/geokit-rails'
gem 'geocoder'
gem 'groupdate'
gem 'pg_search'
gem 'numbers_in_words'
gem 'whenever', :require => false
gem 'audited', '~> 4.3'

gem 'active_hash_relation'
gem 'active_model_serializers', '0.9.2'

gem 'x-editable-rails', github: 'shah743/x-editable-rails'
gem 'pg_backup'
gem 'gmaps4rails'
gem 'friendly_id', '~> 5.2.1'
gem 'time_difference'
gem 'svg-flags-rails', '>= 1.0.0-beta'
gem 'rubyzip', '>= 1.2.1'
gem 'axlsx', git: 'https://github.com/randym/axlsx.git', ref: 'c8ac844'
gem 'axlsx_rails'
gem 'roo',     github: 'roo-rb/roo'
gem 'bootstrap-email'
gem 'delayed_job_active_record'
gem 'capistrano3-delayed-job', '~> 1.0'
gem 'daemons'
gem 'dropzonejs-rails'
gem 'carrierwave'
gem 'fog-aws'
gem 'notifications', '~> 0.6.0'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'pry'
  gem 'rb-readline'
  gem 'better_errors'
  gem 'annotate'
  gem 'binding_of_caller'
  gem 'awesome_print'
  gem 'bullet'
  gem 'lol_dba'
  gem 'seed_dump'
  gem 'letter_opener'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  # Easy installation and use of chromedriver to run system tests with Chrome
  # gem 'chromedriver-helper'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

group :development do
  gem 'capistrano',                 require: false
  gem 'capistrano-rvm',             require: false
  gem 'capistrano-rails',           require: false
  gem 'capistrano-bundler',         require: false
  gem 'capistrano3-puma',           require: false
  gem 'capistrano-upload-config',   require: false
end