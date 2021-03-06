source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.5.1'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.2'
# Repository for collecting Locale data for Ruby on Rails I18n as well as other interesting
gem 'rails-i18n'
# Manage Procfile-based applications
gem 'foreman'
# Flexible authentication solution for Rails with Warden
gem 'devise'
# Translations for the devise gem
gem 'devise-i18n'
# Rails gem of the Bootstrap based admin theme SB Admin 2
gem 'bootstrap_sb_admin_base_v2'
# Use sqlite3 as the database for Active Record
gem 'pg'
# Use Puma as the app server
gem 'puma', '~> 3.11'
# BDD for Ruby
gem 'rspec', '~> 3.8'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
gem 'duktape'
# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
# Use jquery as the JavaScript library
gem 'jquery-rails'
# Use Capistrano for deployment
gem 'capistrano-rails', group: :development
gem 'capistrano-yarn', '~> 2.0', '>= 2.0.2'
# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false
# Help ActiveRecord::Enum feature to work fine with I18n and simple_form
gem 'enum_help'
# Object oriented authorization for Rails applications
gem 'pundit'
# A library for generating fake data such as names, addresses, and phone numbers.
gem 'faker'
# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
# Simple, Heroku-friendly Rails app configuration using ENV and a single YAML file
gem 'figaro'
# When mail is sent from your application, Letter Opener will open a preview in the browser instead of sending.
gem 'letter_opener', :group => :development
# Sidekiq
gem 'sidekiq'
# O Lero-lero Generator é uma ferramenta capaz de gerar frases que 'falam' muita coisa mas que não tem conteúdo algum.
gem 'lerolero_generator'
# Integration of RubyMoney - Money with Rails
gem 'money-rails'
# Easy file attachment management for ActiveRecord C:\Program Files\ImageMagick-7.0.8-Q16\images
gem 'paperclip'
# jQuery UI's JavaScript, CSS, and image files packaged for the Rails 3.1+ asset pipeline
gem 'jquery-ui-rails'
# A fast, safe and extensible Markdown to (X)HTML parser
gem 'redcarpet'
# FriendlyId is the "Swiss Army bulldozer" of slugging and permalink plugins for Active Record
gem 'friendly_id'
# A Scope & Engine based, clean, powerful, customizable and sophisticated paginator for Ruby webapps
gem 'kaminari'
# Translations for the kaminari gem
gem 'kaminari-i18n'
# A Ruby Gem that wraps the functionality of jQuery Raty library, and provides optional IMDB style rating.
gem 'ratyrate'

source 'https://rails-assets.org' do
  # Bootstrap
  gem 'rails-assets-bootstrap', '4.1.1'
  # Bootstrap Notify
  gem 'rails-assets-bootstrap.growl'
  # Animate CSS
  gem 'rails-assets-animate-css'
  # BootboxJS
  gem 'rails-assets-bootbox'
end

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # Provides a better error page for Rails and other Rack apps. Includes source code inspection, a live REPL and local/instance variable inspection for all stack frames.
  gem 'better_errors'
  gem 'pry-byebug'
end

group :development do
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  # Generate Entity-Relationship Diagrams for Rails applications
  gem 'rails-erd'
  # Catches mail and serves it through a dream.
  gem 'mailcatcher'
end

gem 'rails_12factor', group: :production

