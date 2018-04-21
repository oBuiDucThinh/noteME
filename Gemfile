source "https://rubygems.org"

git_source(:github) do |repo_name|
  repo_name = "#{repo_name}/#{repo_name}" unless repo_name.include?("/")
  "https://github.com/#{repo_name}.git"
end

gem "bootstrap-sass"
gem "bootstrap3-datetimepicker-rails"
gem "devise"
gem "devise"
gem "enumerize"
gem "factory_bot_rails"
gem "font-awesome-rails"
gem "jquery-ui-rails"
gem "kaminari"
gem "paperclip", github: "thoughtbot/paperclip"
gem "ransack"
gem "redis-rails"
gem "sidekiq"
gem "coffee-rails", "~> 4.2"
gem "jbuilder", "~> 2.5"
gem "jquery-rails"
gem "mysql2", ">= 0.3.18", "< 0.6.0"
gem "puma", "~> 3.0"
gem "rails", "~> 5.0.7"
gem "sass-rails", "~> 5.0"
gem "turbolinks", "~> 5"
gem "uglifier", ">= 1.3.0"

group :development, :test do
  gem "pry-byebug"
  gem "pry-doc"
  gem "pry-rails"
  gem "pry-stack_explorer"
  gem "rspec-activemodel-mocks"
  gem "rspec-rails"
  gem "timecop"
  gem "byebug", platform: :mri
end

group :development do
  gem "web-console", ">= 3.3.0"
  gem "listen", "~> 3.0.5"
  gem "spring"
  gem "spring-watcher-listen", "~> 2.0.0"
end

gem "tzinfo-data", platforms: [:mingw, :mswin, :x64_mingw, :jruby]
