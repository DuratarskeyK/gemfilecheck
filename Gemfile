source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails'
gem 'sinatra', require: false, git: 'https://github.com/sinatra/sinatra.git'
gem 'activeadmin', git: 'https://github.com/activeadmin/activeadmin'
gem 'inherited_resources', git: 'https://github.com/activeadmin/inherited_resources'
gem 'annotate'
gem 'postgresql'
gem 'redis-semaphore'
# Use Puma as the app server
gem 'puma'
# Use SCSS for stylesheets
gem 'sass-rails'
# Use Uglifier as compressor for JavaScript assets
gem 'uglifier'
gem 'maxminddb'
gem 'sidekiq'
gem 'sidekiq-scheduler'
gem 'sprockets'
gem 'sprockets-es6'
gem 'sentry-raven'
gem 'select2-rails'
gem 'activeadmin-select2', git: 'https://github.com/duratarskeyk/activeadmin-select2'
gem 'oj'
gem 'influxdb'
gem 'slim'

group :development do
  gem 'listen'
  gem 'pry'
end
