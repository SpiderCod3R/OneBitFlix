source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'

gem 'rails', '~> 5.2.3'
gem 'pg', '>= 0.18', '< 2.0'
gem 'puma', '~> 3.12'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'webpacker'

gem 'pg_search', '~> 2.3'
gem 'coffee-rails', '~> 4.2'
gem 'jbuilder', '~> 2.5'

# gem 'bcrypt', '~> 3.1.7'
# gem 'mini_magick', '~> 4.8'

group :development, :test do
  gem 'pry-rails'
  gem 'foreman', '~> 0.86.0'
  gem "mailcatcher"
  gem 'rspec-rails', '~> 3.5'
  gem 'factory_bot_rails'
  gem 'ffaker'
  gem 'guard-livereload', '~> 2.5', '>= 2.5.2'
  gem 'rack-livereload', '~> 0.3.17'
  gem "database_cleaner"
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'awesome_rails_console', '~> 0.4.3'
end

group :test do
  gem 'capybara', '>= 2.15'
  gem 'selenium-webdriver'
  gem 'chromedriver-helper'
end

gem 'bootsnap', '>= 1.1.0', require: false
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

gem 'rack-cors', '~> 1.0', '>= 1.0.3'
gem 'rack-attack', '~> 6.2'

gem 'devise', '~> 4.7', '>= 4.7.1'
gem 'omniauth', '~> 1.9'
