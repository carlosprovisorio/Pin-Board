source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end


gem 'rails', '~> 5.0.3'
gem 'sqlite3'
gem 'puma', '~> 3.0'
gem 'sass-rails', '~> 5.0'
gem 'uglifier', '>= 1.3.0'
gem 'coffee-rails', '~> 4.2'

gem 'jquery-rails'
gem 'turbolinks', '~> 5'
gem 'jbuilder', '~> 2.5'


group :development, :test do
  gem 'byebug', platform: :mri
end

group :development do
  gem 'web-console', '>= 3.3.0'
  gem 'listen', '~> 3.0.5'
  gem 'spring'
  gem 'spring-watcher-listen', '~> 2.0.0'
end
gem 'nokogiri', '~> 1.7', '>= 1.7.2'
gem 'haml', '~> 5.0', '>= 5.0.1'
gem 'bootstrap-sass', '~> 3.3', '>= 3.3.7'
gem 'simple_form', '~> 3.5'
gem 'devise', '~> 4.3'
gem 'paperclip', '~> 5.1'
gem 'masonry-rails', '~> 0.2.4'
gem 'acts_as_votable', '~> 0.10.0'
gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]
