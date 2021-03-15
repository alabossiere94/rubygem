source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '3.0.0'

gem 'rails', '~> 6.1.1'
gem 'pg', '~> 1.1'
gem 'puma', '~> 5.0'
gem 'sass-rails', '>= 6'
gem 'webpacker', '~> 5.0'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.7'
gem 'bootsnap', '>= 1.4.4', require: false

group :development, :test do
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
end

group :development do
  gem 'web-console', '>= 4.1.0'
  gem 'rack-mini-profiler', '~> 2.0'
  gem 'listen', '~> 3.3'
  gem 'spring'
  gem "spring-watcher-listen"
  gem "standard", group: :development
end

group :test do
  gem 'capybara', '>= 3.26'
  gem 'selenium-webdriver'
  gem 'webdrivers'
end

gem "haml-rails", "~> 2.0"
#gem 'bootstrap'
#gem 'jquery-rails' #for bootstrap to work
gem 'font-awesome-sass', '~> 5.15.1' #add icons for styling
gem 'simple_form'
gem 'faker' #fake data for seeds.rb
gem 'devise' #authentication as a User
gem 'friendly_id' 
gem 'ransack' #filter and sort data
gem 'public_activity' #see all activity in the app
gem "rolify" #give users roles (admin, teacher, student)
gem "pundit" #authorization (different roles have different accesses)
gem 'exception_notification', group: :production #notify if errors in production
gem 'pagy' #pagination
gem "chartkick" #charts
gem 'groupdate' #group records by day/week/year
gem 'rails-erd', group: :development #sudo apt-get install graphviz; bundle exec erd
gem 'ranked-model' #give serial/index numbers to items in a list
gem "aws-sdk-s3", require: false #save images and files in production
gem 'active_storage_validations' #validate image and file uploads
