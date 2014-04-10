source 'https://rubygems.org'

gem 'rails', '4.0.4'        # tutorial references 4.0.4
gem 'bootstrap-sass', '2.3.2.0'
gem 'sprockets', '2.11.0'
gem 'bcrypt-ruby', '3.1.2'

group :development, :test do
  gem 'sqlite3', '1.3.8'
  gem 'rspec-rails', '2.13.1'
  gem 'guard-rspec', '2.5.0'
end

group :test do
  gem 'selenium-webdriver', '2.35.1'
  gem 'capybara', '2.1.0'
  
  # gem 'libnotify', '0.8.0'    # Linux
end


gem 'sass-rails', '~> 4.0.0'  # different version than tutorial
gem 'uglifier', '>= 1.3.0'    # different version than tutorial
gem 'coffee-rails', '~> 4.0.0'# different version than tutorial
gem 'jquery-rails'            # different version than tutorial
gem 'turbolinks'              # different version than tutorial
gem 'jbuilder', '~> 1.2'      # different version than tutorial


group :doc do
  gem 'sdoc', require: false  # different version than tutorial
end

# Avoid installing these in dev env't by using 'bundle install --without production'
group :production do
  gem 'pg', '0.15.1'
  gem 'rails_12factor', '0.0.2'
end
