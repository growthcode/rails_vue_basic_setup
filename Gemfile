source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.1.4'
# Use postgresql as the database for Active Record
gem 'pg', '~> 0.18'
# Use Puma as the app server
gem 'puma', '~> 3.7'
# Use SCSS for stylesheets
gem 'sass-rails', '~> 5.0'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier', '>= 1.3.0'
# See https://github.com/rails/execjs#readme for more supported runtimes
# gem 'therubyracer', platforms: :ruby

# Use CoffeeScript for .coffee assets and views
gem 'coffee-rails', '~> 4.2'
# Turbolinks makes navigating your web application faster. Read more: https://github.com/turbolinks/turbolinks
gem 'turbolinks', '~> 5'

# Use Redis adapter to run Action Cable in production
# gem 'redis', '~> 3.0'
# Use ActiveModel has_secure_password
# gem 'bcrypt', '~> 3.1.7'

# Use Capistrano for deployment
# gem 'capistrano-rails', group: :development

# gem 'simple_form'
gem 'active_model_serializers'
gem 'annotate'
gem 'attribute_normalizer'
gem 'awesome_print'
gem 'bootstrap-sass', '~> 3.3.7'
gem 'bootswatch-rails'
gem 'colorize','~> 0.7.5'
gem 'devise'
gem 'factory_bot'
gem 'faker'
gem 'font-awesome-rails'
gem 'jquery-rails' # Dropped in Rails 5.1
gem 'paranoia'
gem 'pry-rails'

# https://github.com/rails/webpacker
gem 'webpacker' # https://mkdev.me/en/mentors/IvanShamatov || https://paweljw.github.io/2017/07/rails-5.1-api-with-vue.js-frontend-part-1-setting-up-a-rails-api-app/
gem 'foreman'

gem 'acts-as-taggable-on'
gem 'bootstrap-sass', '~> 3.3.7'
gem 'bootswatch-rails'
gem 'devise'
gem 'ejs'
gem 'paper_trail'
gem 'paranoia'
gem 'rolify'
gem 'simple_form'
gem 'pghero'

group :development, :test do
  gem 'better_errors' # Better error page for Rack apps (doesn't work when you run "Bundle Exec rails s")
  gem 'bullet' # env development/test: pg, help to kill N+1 queries and unused eager loading
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  gem 'rack-mini-profiler', require: false
  gem 'rubocop'
end

group :development do
  # Access an IRB console on exception pages or by using <%= console %> anywhere in the code.
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'meta_request' # Chrome extension for Rails development
  gem 'rails_db' # Rails Database Viewer and SQL Query Runner
  gem 'traceroute' # A Rake task that helps you find dead routes and unused actions in your Rails
end

group :test do
  gem 'capybara'
  gem 'rspec-rails'
  gem 'selenium-webdriver'
  gem 'timecop' # making it simple to test time-dependent code
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
