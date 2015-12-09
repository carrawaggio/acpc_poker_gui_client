source 'https://rubygems.org'

gem 'rails', '~>3.2'

gem 'rack', '~>1.4'

gem 'acpc_table_manager', '~> 0.0.1'

# For convenient styling macros and SASS
gem 'compass-rails', '~> 1.0'
gem 'blueprint-rails', '~> 0.2'

# To interpret Coffeescript in HAML
gem 'coffee-filter', '~> 0.1'

# JavaScript library
gem 'jquery-rails', '~> 2.2'

# Enable HAML format views. Prettier than ERB format views.
gem "haml", '~> 3.1'

# For deployment. Phusion Passenger integrates the rails app. with Apache.
gem 'passenger', '~>4.0'

# To manage background processes
gem 'god'

# Improved logging output
gem 'awesome_print'

# For password encryption
gem 'bcrypt', '~> 3.1.5', require: "bcrypt"

gem 'js-routes'

# Gems used only for assets and not required
# in production environments by default.
group :assets do
  # JavaScript library
  gem 'jquery-ui-rails'

  gem 'sass-rails', '>= 3.2'
  gem "bootstrap-sass", '~> 3.3.1'
  # Recommended by Bootstrap for adding browser vendor prefixes automatically
  gem 'autoprefixer-rails'
  gem 'zen-grids'

  gem 'coffee-rails'
  gem 'uglifier'

  # compass uses this for sprites
  gem 'chunky_png'

  # native c library for png routines to speed up chunky_png
  gem 'oily_png'
end

group :development do
  # YARD documentation library
  gem 'yard'

  # To interpret markdown
  gem 'kramdown'

  # Better error information
  gem 'better_errors'
  gem 'binding_of_caller'
  gem 'meta_request'

  # Not strictly necessary but makes
  # testing through a VM network much faster
  # because WeBrick needs a line of configuration
  # changed, otherwise it's impossibly slow
  gem 'thin'

  # Static code analysis
  gem 'rails_best_practices'

  gem 'pry-rails'
end
