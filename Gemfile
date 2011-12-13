source 'http://rubygems.org'


# Setup common for all environments
gem 'rails', '3.1.3'
gem 'therubyracer'
gem 'jquery-rails'


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.1.5'
  gem 'coffee-rails', '~> 3.1.1'
  gem 'uglifier', '>= 1.0.3'
end


# Setup for environment during development
group :development do
  gem 'sqlite3'
  gem 'rspec-rails'
end


# Setup for environment during tests
group :test do
  #  gem 'nokogiri'
  gem 'sqlite3'
  gem "rspec"
  gem 'webrat'  # Required for some rspec methods
  gem 'turn', '0.8.2', :require => false
end


# Setup for environment during production
group :production do
  gem 'pg'   # Remember that Hiroku does not offer sqlite or mysql
  gem 'thin'
  gem 'heroku'
end
