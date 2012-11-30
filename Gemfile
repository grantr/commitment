source 'https://rubygems.org'

gem 'rails',     github: 'rails/rails'
gem 'journey',   github: 'rails/journey'

# Gems required for persistence
group :persistence do
  gem 'riak-client'
end

# Gems required for API requests
group :api do
  # gem 'jbuilder'
  gem 'active_model_serializers'
  gem 'rails-api'
end

group :runtime do
  gem 'puma'
end

group :development, :test do
  gem 'debugger'
end

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sprockets-rails', github: 'rails/sprockets-rails'
  gem 'sass-rails',   github: 'rails/sass-rails'
  gem 'coffee-rails', github: 'rails/coffee-rails'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', platforms: :ruby

  gem 'uglifier', '>= 1.0.3'
end

# Gems required for web pages
group :html do
  gem 'jquery-rails'

  # Turbolinks makes following links in your web application faster. Read more: https://github.com/rails/turbolinks
  gem 'turbolinks'
end

# ActiveRecord dependencies. Why is activerecord required by rails?
group :activerecord do
  gem 'arel',      github: 'rails/arel'
  gem 'activerecord-deprecated_finders', github: 'rails/activerecord-deprecated_finders'
end

