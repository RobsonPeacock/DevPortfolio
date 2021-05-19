# frozen_string_literal: true

source 'https://rubygems.org'

ruby '2.4.9'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?('/')
  "https://github.com/#{repo_name}.git"
end

gem 'coffee-rails', '~> 4.2'
gem 'jbuilder', '~> 2.5'
gem 'jquery-rails'
gem 'pg', '~> 0.18'
gem 'puma', '~> 4.3'
gem 'rails', '~> 5.0.1'
gem 'sass-rails', '~> 5.0'
gem 'turbolinks', '~> 5'
gem 'uglifier', '>= 1.3.0'

group :development, :test do
  gem 'byebug', platform: :mri
end

group :development do
  gem 'listen', '~> 3.0.5'
  gem 'rubocop', '~> 0.84.0', require: false
  gem 'rubocop-performance', '~> 1.6', require: false
  gem 'rubocop-rails', '~> 2.5', '>= 2.5.2', require: false
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  gem 'web-console', '>= 3.3.0'
end

gem 'bootstrap', '~> 4.4.1'
gem 'carrierwave', '~> 2.1'
gem 'carrierwave-aws', '~> 1.5'
gem 'cocoon', '~> 1.2', '>= 1.2.14'
gem 'coderay', '~> 1.1', '>= 1.1.2'
gem 'devise', '~> 4.7', '>= 4.7.1'
gem 'dotenv-rails', '~> 2.7', '>= 2.7.5'
gem 'font-awesome-rails', '~> 4.7', '>= 4.7.0.5'
gem 'friendly_id', '~> 5.1.0'
gem 'gritter', '~> 1.2'
gem 'jquery-ui-rails', '~> 6.0', '>= 6.0.1'
gem 'kaminari', '~> 1.2'
gem 'mini_magick', '~> 4.10', '>= 4.10.1'
gem 'petergate', '~> 2.0', '>= 2.0.1'
gem 'redcarpet', '~> 3.5'
gem 'redis', '~> 3.3', '>= 3.3.3'
gem 'robson_view_tool', '~> 0.1.0'
gem 'twitter', '~> 7.0'
gem 'tzinfo-data', platforms: %i[mingw mswin x64_mingw jruby]
