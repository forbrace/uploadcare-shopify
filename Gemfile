source 'https://rubygems.org'
ruby "2.2.2"

gem 'shopify-sinatra-app', '~> 0.2.0'
gem 'sinatra-activerecord'
gem 'rack-flash3', require: 'rack-flash'

group :production do
  gem 'pg'
end

group :development, :test do
  gem 'sqlite3'
  gem 'byebug'
end

group :development do
  gem 'rake'
  gem 'foreman'
  gem 'dotenv'
end

group :test do
  gem 'mocha', require: false
  gem 'minitest'
  gem 'rack-test'
  gem 'fakeweb'
end
