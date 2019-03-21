# frozen_string_literal: true

source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '~> 2.5.1'

gem 'rails', '~> 5.2.0'

gem 'acts_as_votable', '~> 0.11.1'
gem 'autoprefixer-rails'
gem 'bootsnap', '>= 1.1.0', require: false
gem 'coffee-rails', '~> 4.2'
gem 'dalli'
gem 'devise', '~> 4.4'
gem 'devise-i18n'
gem 'fast_jsonapi'
gem 'google-api-client', '~> 0.11'
gem 'jbuilder', '~> 2.5'
gem 'jquery-ui-rails', '~> 5.0', '>= 5.0.5'
gem 'mini_magick'
gem 'omniauth-facebook'
gem 'omniauth-google-oauth2'
gem 'omniauth-oauth2'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.11'
gem 'react-rails'
gem 'redis'
gem 'sanitize', '~> 5.0'
gem 'sassc-rails'
gem 'searchkick'
gem 'serviceworker-rails', '~> 0.5.5'
gem 'sidekiq'
gem 'sidekiq-scheduler', '~> 3.0'
gem 'timecop', '~> 0.9.1'
gem 'turbolinks', '~> 5'
gem 'uglifier', '>= 1.3.0'
gem 'webpacker'
gem 'webpush'

# JS runtime env:
gem 'mini_racer'

# SEO
gem 'sitemap_generator'

# necessary dependencies
gem 'sprockets', '>= 3.0.0'
gem 'sprockets-es6'

gem 'i18n-js'
gem 'rails-i18n', '~> 5.1'

gem 'foundation_emails'
gem 'inky-rb', require: 'inky'
gem 'premailer-rails' # Stylesheet inlining for email **

# CMS
gem 'chartkick'
gem 'faker', '~> 1.8'
gem 'foundation-rails'
gem 'foundation_rails_helper'
gem 'groupdate'
gem 'jquery-rails'
gem 'kaminari'
gem 'tinymce-rails'
gem 'tinymce-rails-imageupload', '~> 4.0.0.beta'

gem 'rollbar'
gem 'route_translator'

group :development, :test do
  gem 'bundler-audit', require: false
  gem 'byebug', platforms: %i[mri mingw x64_mingw]
  gem 'capybara', '~> 3.3'
  gem 'factory_bot_rails'
  gem 'fuubar'
  gem 'pry-byebug'
  gem 'rails-controller-testing'
  gem 'rb-readline'
  gem 'rspec-its'
  gem 'rspec-rails'
  gem 'shoulda-matchers', '~> 3.1'
end

group :test do
  gem 'action-cable-testing'
  gem 'database_cleaner'
  gem 'pronto'
  gem 'pronto-reek', require: false
  gem 'pronto-rubocop', require: false
  gem 'rubocop-rspec'
  gem 'simplecov', require: false
  gem 'webmock'
end

group :development do
  # deploy
  gem 'capistrano'
  gem 'capistrano-artrails', '~> 0.1.7'
  gem 'capistrano-ext'
  gem 'capistrano-local-precompile'
  gem 'capistrano-rails'
  gem 'capistrano-rsync-bladrak'
  gem 'capistrano-rvm'
  gem 'capistrano-scm-copy'
  gem 'capistrano3-puma'

  gem 'awesome_print'
  gem 'bullet'
  gem 'guard-reek'
  gem 'guard-rspec', require: false
  gem 'guard-rubocop'
  gem 'guard-shell'
  gem 'letter_opener'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'pry-rails'
  gem 'spring'
  gem 'spring-commands-rspec'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'web-console', '>= 3.3.0'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
