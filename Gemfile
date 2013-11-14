source 'https://rubygems.org'
ruby '2.0.0'
#ruby-gemset=railstutorial_rails_4_0

gem 'rails', '4.0.1'

group :development, :test do
  gem 'sqlite3', '1.3.8'
  gem 'rspec-rails', '2.13.1'
end

group :test do
  gem 'selenium-webdriver', '2.35.1'
  gem 'capybara', '2.1.0'
end

gem 'sass-rails', '4.0.1'
gem 'uglifier', '2.1.1'
gem 'coffee-rails', '4.0.1'
gem 'jquery-rails', '3.0.4'
gem 'turbolinks', '1.1.1'
gem 'jbuilder', '1.0.2'

group :doc do
  gem 'sdoc', '0.3.20', require: false
end

group :production do
  gem 'pg', '0.15.1'
  gem 'rails_12factor', '0.0.2'
end

#IMPORTANT! Some of the defaults have changed in Capybara 2.1. If you're experiencing failures,
#please revert to the old behaviour by setting:

 #   Capybara.configure do |config|
  #    config.match = :one
   #   config.exact_options = true
    #  config.ignore_hidden_elements = true
     # config.visible_text_only = true
    #end

#If you're migrating from Capybara 1.x, try:

#    Capybara.configure do |config|
 #     config.match = :prefer_exact
  #    config.ignore_hidden_elements = false
   # end

