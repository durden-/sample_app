source 'http://rubygems.org'

gem 'rails', '3.1.0'
gem 'execjs'
gem 'therubyracer'
gem 'gravatar_image_tag'

group :production, :staging do
  gem "pg"
end

group :development do
  gem 'pg'
  gem 'rspec-rails'
  gem 'annotate', :git => 'git://github.com/ctran/annotate_models.git'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails', "  ~> 3.1.0"
  gem 'coffee-rails', "~> 3.1.0"
  gem 'uglifier'
end

gem 'jquery-rails'

group :test do
  # Pretty printed test output
  gem 'sqlite3'
  gem 'webrat'
  gem 'turn', :require => false
  gem 'factory_girl_rails', '> 1.0'
end
