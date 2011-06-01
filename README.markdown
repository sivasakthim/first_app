This is just a test app.
This will be wiped off at any moment
here

Creating vivid-sunrise-863... done, stack is bamboo-ree-1.8.7
http://vivid-sunrise-863.heroku.com/ | git@heroku.com:vivid-sunrise-863.git
Git remote heroku added


source 'http://rubygems.org'
gem 'rails', '3.0.0'
gem 'sqlite3-ruby', '1.2.5', :require => 'sqlite3'
group :development do
gem 'rspec-rails', '2.0.1'
end
group :test do
gem 'rspec', '2.0.1'
gem 'webrat', '0.7.1'
end


bundle install

rails generate rspec:install


Autotest
gem install autotest -v 4.3.2
gem install autotest-rails-pure -v 4.1.0
gem install autotest-fsevent -v 0.2.2
gem install autotest-growl -v 0.2.4


vi .autotest
require 'autotest/growl'
require 'autotest/fsevent'



Red, Green, Refactor cycle
