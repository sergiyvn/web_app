# A sample Gemfile
source "https://rubygems.org"
ruby '2.0.0'
#ruby-gemset=railstutorial_rails_4_0

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails'
gem 'bootstrap-sass'
gem 'bcrypt'
gem 'sass-rails'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '4.0.1'
gem 'jquery-rails', '3.0.4'
gem 'turbolinks', '2.5.3'
gem 'jquery-turbolinks'
gem 'jbuilder', '~> 2.0'
gem 'faker', '1.1.2'                    #заполнитель образцов данных / the sample data populator
gem 'will_paginate', '3.0.4'            #for pagination
gem 'bootstrap-will_paginate', '0.0.9'  #for pagination

group :development, :test do
  gem 'sqlite3', '1.3.8'
end

group :test do
  gem 'selenium-webdriver', '2.35.1'
  gem 'capybara', '2.1.0'
  gem 'factory_girl_rails', '4.2.1'
  gem 'cucumber-rails', '1.4.0', :require => false
  gem 'database_cleaner', github: 'bmabey/database_cleaner'
end

group :doc do
  gem 'sdoc', '0.4.0', require: false
end

group :production do
  gem 'pg', '0.15.1'
  gem 'rails_12factor'
end


# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
#gem 'tzinfo-data', platforms: [:mingw, :mswin]