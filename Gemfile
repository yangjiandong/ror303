source 'http://rubygems.org'

gem 'rails', '3.0.3'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

if defined?(JRUBY_VERSION)
    # gem 'jdbc-sqlite3'
    gem 'activerecord-jdbc-adapter'
    gem 'activerecord-jdbcsqlite3-adapter'
    gem 'activerecord-jdbcmysql-adapter'
    gem 'activerecord-jdbcmssql-adapter'
    gem 'jruby-openssl'
    gem 'jruby-rack'
    gem 'rmagick4j'
else
    gem 'sqlite3-ruby', :require => 'sqlite3'
    gem 'ruby-oci8', '~> 2.0.4'
    gem 'rmagick'
end

# gem 'mysql2'

# Authentication/Authorization
gem 'devise'
gem 'cancan'
gem 'jquery-rails'

# Use unicorn as the web server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger (ruby-debug for Ruby 1.8.7+, ruby-debug19 for Ruby 1.9.2+)
# gem 'ruby-debug'
# gem 'ruby-debug19'

# Bundle the extra gems:
# gem 'bj'
# gem 'nokogiri'
# gem 'sqlite3-ruby', :require => 'sqlite3'
# gem 'aws-s3', :require => 'aws/s3'

# Bundle gems for the local environment. Make sure to
# put test-only gems in this group so their generators
# and rake tasks are available in development mode:
group :development, :test do
  gem 'capybara'
  gem 'cucumber'
  gem 'cucumber-rails'
  gem 'rspec'
  gem 'rspec-rails'
  gem 'shoulda'
  gem 'factory_girl'
  gem 'factory_girl_rails'
  gem 'autotest'
  #gem 'annotate-models'
  gem 'annotate',           '>= 2.4.0'
  gem 'ffaker',             '>= 0.4.0' # Fast Faker for `rake crm:demo:load`
  gem 'rails3-generators'
  gem 'warbler'
  gem 'bullet'
  gem 'mongrel'
  gem 'webrat'

end
