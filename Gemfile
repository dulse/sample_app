source 'https://rubygems.org'

gem 'rails', '3.2.6'


# Gems used only for assets and not required
# in production environments by default.
group :assets do
  gem 'sass-rails',   '~> 3.2.3'
  gem 'coffee-rails', '~> 3.2.1'

  # See https://github.com/sstephenson/execjs#readme for more supported runtimes
  # gem 'therubyracer', :platforms => :ruby

  gem 'uglifier', '>= 1.0.3'
end

group :development do
  gem 'rspec-rails', "~>2.8"
  gem 'sqlite3'
  gem 'annotate'

end

group :test do
	gem 'rspec', "~> 2.8"
	gem 'webrat'
	gem 'sqlite3'
	gem 'factory_girl_rails', '1.0'
end

group :production, :staging do
  gem "pg"
end

gem 'jquery-rails'
