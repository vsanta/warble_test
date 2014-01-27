source 'https://rubygems.org'

gem 'rails', '3.2.16'

# Bundle edge Rails instead:
# gem 'rails', :git => 'git://github.com/rails/rails.git'

gem 'activerecord-jdbcsqlite3-adapter'

gem 'jruby-openssl'

gem 'activeadmin', git: 'https://github.com/gregbell/active_admin.git'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  gem 'therubyrhino'

  gem 'uglifier', '>= 1.0.3'
end

gem 'jquery-rails'

platforms :jruby do
  gem 'jruby-jars', "1.7.8"
  gem 'jruby-openssl', :require => false
  gem 'rubyzip'
  group :development do
    gem 'coffee-rails-source-maps'
    gem 'jruby-lint'
    gem 'warbler', "1.4.0.beta2"
    gem "rails-erd"
    gem 'trinidad'
  end
end

group :development, :test do
  gem 'ffaker'
  gem 'newrelic_rpm'
  # Fix to kill webkit_server process in jruby
  # https://github.com/thoughtbot/capybara-webkit/issues/606
  gem 'capybara-webkit', github: 'rupurt/capybara-webkit', branch: 'jruby-kill-process'
  gem "codeclimate-test-reporter", '< 0.1'
  gem 'bullet'
  gem 'factory_girl_rails'
  gem 'launchy'
  gem 'license_finder', require: false
  gem 'rails_best_practices', require: false
  gem 'rspec-rails'
  gem 'sextant'
  gem 'shoulda'
  gem 'simple_bdd'
  gem 'whitespace', require: false
  gem 'valid_attribute'
  gem 'fixture_builder'
  gem 'jasmine-rails'
  gem 'jasmine-jquery-rails'
  gem 'pry-nav'
  gem 'brakeman', require: false
  gem 'quiet_assets'
  gem 'roo'
  gem 'spork', '~> 1.0rc'
  gem 'spork-rails'
end


# To use ActiveModel has_secure_password
# gem 'bcrypt-ruby', '~> 3.0.0'

# To use Jbuilder templates for JSON
# gem 'jbuilder'

# Use unicorn as the app server
# gem 'unicorn'

# Deploy with Capistrano
# gem 'capistrano'

# To use debugger
# gem 'debugger'
