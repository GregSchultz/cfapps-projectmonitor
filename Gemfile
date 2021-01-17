source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

## upgrade : http://railsdiff.org/4.2.6/6.0.3.4

# ruby '~> 2.3.1'
ruby '2.5.0'

gem 'acts-as-taggable-on'
gem 'airbrake', '~> 4.3.8'
gem 'bourbon'
gem 'choices'
gem 'daemons'
gem 'delayed_job_active_record'
gem 'delayed_job_web'
# gem 'devise', '~> 4.2.0'
gem 'devise', '~> 4.7.3'
gem 'devise-encryptable'
gem 'draper', '~> 4.0.1'

# gem 'sass-rails'
gem 'sass-rails', '>= 6'
# Transpile app-like JavaScript. Read more: https://github.com/rails/webpacker
gem 'webpacker', '~> 4.0'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks		
# gem 'turbolinks', '~> 5'

gem 'bootstrap-sass'
gem 'haml-rails'
gem 'html2haml', '~> 2.2.0'
# gem 'jquery-rails'
gem 'nokogiri', '1.8.5'
gem 'loofah', '2.2.2'

gem 'oauth2', '1.4.0'
gem 'omniauth', '~> 1.8.1'
gem 'omniauth-google-oauth2', '0.5.3'
gem 'omniauth-oauth2', '1.5.0'

# gem 'rack-protection', '1.5.5'
gem 'rack-protection', '2.1.0'
gem 'pivotal-tracker'
# gem 'rails', '~> 4.2.6'
gem 'rails', '~> 6.0.3', '>= 6.0.3.4'
# gem 'rails-dom-testing', '~> 1.0.8'
gem 'rails-dom-testing', '~> 2.0.0'
gem 'rake'
gem 'whenever', require: false
gem 'rails-backbone'
# gem 'coffee-rails'
gem 'eco'
#gem install mysql2 --source 'https://rubygems.org/' -- --with-ldflags=-L/usr/local/opt/openssl/lib --with-cppflags=-I/usr/local/opt/openssl/include
#use above command to get mysql2 gem installed
gem 'mysql2'
gem 'eventmachine'
gem 'em-http-request'
gem 'newrelic_rpm'
# gem 'unicorn'
# Use Active Storage variant		
# gem 'image_processing', '~> 1.2'

# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.4.2', require: false

# gem 'uglifier'
gem 'clockwork'
# gem 'jbuilder'
gem 'jbuilder', '~> 2.7'
gem 'ruby-openid'
gem 'kramdown'
# gem 'lograge', '~> 0.4'
gem 'lograge', '~> 0.11.2'

group :production do
  gem 'rails_12factor'
end

group :test do
  gem 'vcr'
  gem 'webmock'
end

# NOTE: anything that will not work in travis should be here
group :development do
  gem 'heroku_san'
  gem 'guard-livereload', require: false
  gem 'rb-fsevent'
  # gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'  
  gem 'spring-commands-rspec'
  gem 'better_errors'
  gem 'foreman'
  gem 'guard-ctags-bundler'
  # gem 'quiet_assets'
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :test, :development do
  gem 'awesome_print'
  gem 'launchy'
  gem 'jshint_on_rails'
  gem 'rspec-rails'
  gem 'shoulda-matchers'

  # gem 'capybara'
  gem 'capybara', '>= 2.15'		   	
  gem 'selenium-webdriver'		
  # Easy installation and use of web drivers to run system tests with browsers		
  gem 'webdrivers'  

  gem 'jasmine'
  gem 'factory_girl_rails'
  gem 'guard'
  gem 'database_cleaner'
  # gem 'capybara-webkit'
  gem 'pry-nav'
  gem 'pry-rails'
  gem 'pry'
  gem 'vagrant'
  gem 'timecop'
end
