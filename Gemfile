source 'https://ruby.taobao.org/'

gemspec

gem 'rspec-rails', '>=2.14.0'
gem 'therubyrhino'
gem 'therubyracer'
gem 'jasmine'
gem 'headless'
gem 'selenium-webdriver'
gem 'coffee-script'
# gem 'puma'
gem 'eventmachine'
gem 'faye-websocket', '0.10.0'
gem 'simplecov'
gem 'ruby_gntp'
gem 'guard'
gem 'guard-rspec'
gem 'guard-coffeescript'
gem 'rb-fsevent'

platforms :jruby do
  gem 'activerecord-jdbcsqlite3-adapter', :require => 'jdbc-sqlite3', :require => 'arjdbc'
end
platforms :ruby do
  gem 'sqlite3'
end
