source 'https://rubygems.org'

ruby "2.3.0"
gem 'rails', '~> 5.0.0'

gem 'foundation-rails'
gem 'slim'
gem 'slim-rails'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'
gem 'jquery-rails'
gem 'turbolinks', '~> 5'

group :development, :test do
  gem 'byebug', platform: :mri
end

group :development do
  gem 'puma'
  gem 'web-console'
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end

group :production do
  gem 'unicorn'
  gem 'heroku-deflater', '>= 0.4.1'
  gem 'rails_12factor'
  gem 'rack-timeout'
end
