source 'https://rubygems.org'
git_source(:github) { |repo| "https://github.com/#{repo}.git" }

ruby '2.6.3'

## json serializer
gem 'active_model_serializers'
# Reduces boot times through caching; required in config/boot.rb
gem 'bootsnap', '>= 1.1.0', require: false
gem 'foreman'
# Bundle edge Rails instead: gem 'rails', github: 'rails/rails'
gem 'rails', '~> 5.2.3'
# Use postgresql as the database for Active Record
gem 'pg', '>= 0.18', '< 2.0'
# Use Puma as the app server
gem 'puma', '~> 3.11'
# Build JSON APIs with ease. Read more: https://github.com/rails/jbuilder
gem 'jbuilder', '~> 2.5'
## Session Store
gem 'redis-rails'
gem 'seed-fu'
## View Template
gem 'slim-rails'
gem 'webpacker', '~> 4.0'

group :development, :test do
  # N+1問題検出
  gem 'bullet'
  # Call 'byebug' anywhere in the code to stop execution and get a debugger console
  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
  # テストデータ生成
  gem 'factory_bot_rails'
  # RSpec
  gem 'rspec-rails'
end

group :development do
  # エラー画面の高機能化
  gem 'better_errors'
  # エラー画面にirbを追加
  gem 'binding_of_caller'
  gem 'capistrano-rails', group: :development
  # 言語ファイル(ja.yml)生成
  gem 'i18n_generators'
  gem 'listen', '>= 3.0.5', '< 3.2'
  # コーディングルールチェック
  gem 'rubocop', require: false
  # ER図の生成
  gem 'rails-erd', require: false
  # Spring speeds up development by keeping your application running in the background. Read more: https://github.com/rails/spring
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
  # Access an interactive console on exception pages or by calling 'console' anywhere in the code.
  gem 'web-console', '>= 3.3.0'
end

group :test do
  # Adds support for Capybara system testing and selenium driver
  gem 'capybara', '>= 2.15'
  # Easy installation and use of chromedriver to run system tests with Chrome
  gem 'chromedriver-helper'
  gem 'selenium-webdriver'
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
