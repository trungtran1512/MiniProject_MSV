source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '~> 5.1.5'

gem 'puma', '~> 3.7'

gem 'sass-rails', '~> 5.0'

gem 'uglifier', '>= 1.3.0'

gem 'coffee-rails', '~> 4.2'

gem 'turbolinks', '~> 5'

gem 'jquery-turbolinks', '~> 2.1'

gem 'masonry-rails', '~> 0.2.4'

gem 'simple_form', '~> 3.5', '>= 3.5.1'

gem 'jbuilder', '~> 2.5'

gem 'jquery-rails', '~> 4.3', '>= 4.3.1'

gem 'bootstrap-sass', '~> 3.3', '>= 3.3.7'

gem 'haml', '~> 5.0', '>= 5.0.4'

gem 'devise', '~> 4.4', '>= 4.4.3'

gem 'paperclip', '~> 6.0'

gem 'aws-sdk', '~> 3.0', '>= 3.0.1'

gem 'acts_as_votable', '~> 0.11.1'

gem 'kaminari', '~> 1.1', '>= 1.1.1'

gem 'bootstrap-kaminari-views', '~> 0.0.5'
gem 'listen', '~> 3.1.5'

group :development, :test do

  gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]

  gem 'capybara', '~> 2.13'

  gem 'selenium-webdriver'

  gem 'cucumber', '~> 3.1'
end


group :development do

  gem 'sqlite3'

  gem 'web-console', '>= 3.3.0'

  gem 'listen', '~> 3.1.5'

  gem 'spring'

  gem 'spring-watcher-listen', '~> 2.0.0'
end


group :test, :production do

  gem 'rails_12factor'

  gem 'pg'
  
end

gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
