source 'https://rubygems.org'
ruby '2.0.0'

gem 'sinatra'
gem 'sinatra-contrib'

gem 'activerecord'
gem 'sinatra-activerecord'
gem 'sinatra-flash'
gem 'sinatra-redirect-with-flash'

gem 'capistrano', '2.15.5'
gem 'net-ssh', '2.7.0'
gem 'rake'

group :development, :test do
	gem 'sqlite3'
	gem 'tux'

	gem 'better_errors'
	gem 'binding_of_caller'
	gem 'pry-debugger'
  
  gem 'capybara'
  gem 'factory_girl'
	gem 'rspec'
end

group :production do
	gem 'pg'
end