source 'https://rubygems.org'

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem 'rails', '~> 5.1.6'
gem 'mysql2', '>= 0.3.18', '< 0.5', platform: :ruby
gem 'nokogiri', :platform => :ruby

if platform :mswin, :mingw, :x64_mingw do
  gem 'mysql2', '>= 0.3.18', '< 0.5', :platform => [:mswin, :mingw]
  gem 'nokogiri', :platform => [:mswin, :mingw]
  gem 'bcrypt', '~> 3.1.7', :platform => [:ruby, :mingw, :x64_mingw]
end

  gem 'puma', '~> 3.7'
  gem 'sass-rails', '~> 5.0'
  gem 'uglifier', '>= 1.3.0'
  gem 'coffee-rails', '~> 4.2'
  gem 'turbolinks', '~> 5'
  gem 'jbuilder', '~> 2.5'
  gem 'bcrypt', '~> 3.1.7'

  gem 'bootstrap', '~> 4.0.0'
  gem 'jquery-rails'
  gem 'jquery-ui-rails'
  gem 'popper_js', '~> 1.12.9'
  gem 'font-awesome-rails', '~> 4.7', '>= 4.7.0.3'
  gem 'figaro'
  gem 'devise'

  group :development, :test do
    gem 'byebug', platforms: [:mri, :mingw, :x64_mingw]
    gem 'capybara', '~> 2.13'
    gem 'selenium-webdriver'
    gem 'rspec-rails', '~> 3.7'
  end

  group :test do
    gem 'database_cleaner', '~> 1.6', '>= 1.6.1'
  end

  group :development do
    gem 'capistrano', '3.10.1'
    gem 'capistrano-rvm'
    gem 'capistrano3-nginx'
    gem 'capistrano3-puma'
    gem 'capistrano-rails'
    gem 'capistrano-rails-db'
    gem 'capistrano-rails-console'
    gem 'capistrano-upload-config'
    gem 'capistrano-figaro-yml'
    gem 'sshkit-sudo'
  end


  group :development do
    gem 'web-console', '>= 3.3.0'
  end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
  gem 'tzinfo-data', platforms: [:mingw, :mswin, :x64_mingw, :jruby]

end