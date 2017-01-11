source 'https://rubygems.org'

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.0.0', '>= 5.0.0.1'
gem 'mysql2', '~> 0.4.4'
gem 'puma', '~> 3.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'

gem 'jquery-rails'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'
# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# See https://github.com/rails/execjs#readme for more supported runtimes
gem 'therubyracer', platforms: :ruby

gem 'dotenv-rails'
gem 'devise'
gem 'kaminari'
gem 'pundit'
gem 'aasm'
gem 'seed-fu'
gem 'slim-rails'
gem 'draper', '>= 3.0.0.pre1'
gem 'twitter-bootstrap-rails'

group :development, :test do
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platform: :mri
  gem 'rspec-rails'

  gem 'pry-rails'
  gem 'pry-byebug'
  gem 'rspec-rails'
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'factory_girl_rails'
  gem 'capybara'
  gem 'shoulda-matchers'
  gem 'faker'

  # gem 'turnip'
  # gem 'poltergeist'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console'
  gem 'listen', '~> 3.0.5'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'brakeman'
  gem 'rubocop', require: false
  gem 'html2slim', require: false
  gem 'rails-erd', require: false
  gem 'annotate'

  gem 'guard'
  gem 'guard-rspec', require: false
  gem 'guard-rubocop', require: false
  gem 'mailcatcher', require: false
end

group :test do
  gem 'database_cleaner'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
