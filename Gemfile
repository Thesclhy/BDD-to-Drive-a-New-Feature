source 'https://rubygems.org'

ruby '2.6.6'
gem 'rails', '~> 6.1.7'
gem 'puma', '~> 5.6'

group :development, :test do
  gem 'sqlite3', '~> 1.6'
  gem 'byebug', '~> 11.1'
  gem 'database_cleaner-active_record', '~> 2.1'
  gem 'capybara', '~> 3.36.0'
  gem 'launchy', '~> 2.5'
  gem 'rspec-rails', '~> 5.1'
  gem 'ZenTest', '~> 4.12'
end

group :test do
  gem 'cucumber-rails', '~> 2.6', require: false
  gem 'simplecov', require: false
end

group :production do
  gem 'pg', '~> 1.5'
end

gem 'sassc-rails', '~> 2.1'
gem 'uglifier', '>= 4.2'
gem 'jquery-rails', '~> 4.6'
gem 'sprockets-rails', '~> 3.4'
