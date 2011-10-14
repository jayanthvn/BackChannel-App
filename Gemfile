source 'http://rubygems.org'

gem 'heroku'

gem 'rails', '3.1.0'

# Bundle edge Rails instead:
# gem 'rails',     :git => 'git://github.com/rails/rails.git'



gem 'will_paginate', '3.0.pre2'

gem 'pg', :group => :production

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', "  ~> 3.1.0"
  gem 'coffee-rails', "~> 3.1.0"
  gem 'uglifier'
  gem 'will_paginate', '3.0.pre2'
  gem 'webrat', '>= 0.4.3'
  gem 'test-unit', '>=2.4.0'
  gem 'rack', '1.3.3'

end

gem 'jquery-rails'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'ruby-debug19', :require => 'ruby-debug'
group :development do
  gem 'rspec-rails', '2.6.1'
  gem 'sqlite3'
#  gem 'faker', '0.3.1'
end

group :test do
  # Pretty printed test output
  gem 'turn', :require => false
  
end

group :production do
  # gems specifically for Heroku go here
  gem "pg"
end

gem "rspec", ">=2.6.0"
