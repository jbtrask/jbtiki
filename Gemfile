source 'https://rubygems.org'

gem 'rails'
gem 'jquery-rails'
gem 'bootstrap-sass'
gem 'omniauth'
gem 'omniauth-google-oauth2'
gem 'simple_form'
gem 'figaro'
gem 'psych'

group :assets do
	gem 'sass-rails'
	gem 'coffee-rails'
	gem 'uglifier'
end

group :test, :development do
	gem 'sqlite3'
	gem 'rspec-rails'
	gem 'factory_girl_rails'
end

group :development do
	gem 'quiet_assets'
	gem 'better_errors'
	gem 'hub', :require => nil
	gem 'binding_of_caller', :platforms => [:mri_19, :rbx]
end

group :test do
	gem 'capybara'
	gem 'database_cleaner'
	gem 'email_spec'
end