source 'http://rubygems.org'

gem 'rails', '3.1.0'
gem 'bootstrap-sass', '3.1.1.1'
gem 'bcrypt-ruby', '3.0.1'
gem 'faker', '1.3.0'
gem 'will_paginate', '3.0.5'
gem 'bootstrap-will_paginate', '0.0.6'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'
group :development do
  gem 'sqlite3' , '1.3.9'
  gem 'annotate', '2.6.3'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.1.5'
  gem 'coffee-rails', '~> 3.1.1'
  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer'
  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails' , '3.1.0'

group :development, :test do 
  gem 'rspec-rails', '<= 2.14.8'
  gem 'guard-rspec', '0.5.5'
  gem 'guard-spork', '0.3.2'
  gem 'spork', '0.9.0'
end

group :test do
gem 'capybara', '1.1.2'
gem 'factory_girl_rails', '1.4.0'
gem 'cucumber-rails', '1.2.1', require: false
gem 'database_cleaner', '0.7.0'
end

group :production do
	gem 'pg' , '0.17.1'
end
# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'

group :test do
  # Pretty printed test output
  gem 'turn', '~> 0.8.3', :require => false
end
