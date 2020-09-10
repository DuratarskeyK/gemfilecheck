source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~>6.0'
gem 'sinatra', require: false, git: 'https://github.com/sinatra/sinatra.git'
gem 'activeadmin'
gem 'annotate'
gem 'postgresql'
gem 'redis-semaphore'
# Use Puma as the app server
gem 'puma'
# Use SCSS for stylesheets
gem 'sass-rails', '>= 6'
gem 'maxminddb'
gem 'webpacker', '~>4.0'
gem 'sidekiq'
gem 'sidekiq-scheduler'
gem 'sentry-raven'
gem 'oj'
gem 'influxdb'
gem 'slim'
gem 'bootsnap', '>= 1.4.2', require: false

gem 'e2mmap'
gem 'thwait'

group :development do
  gem 'listen'
  gem 'pry'
end
