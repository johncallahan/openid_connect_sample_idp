source 'http://rubygems.org'

ruby '2.5.1'

gem 'rails', '~>3.2'
gem 'jquery-rails'
gem 'squeel'
gem 'constant_cache'
gem 'html5_validators'
gem 'validate_url'
gem 'validate_email'
gem 'fb_graph'
gem 'rack-oauth2'
gem 'openid_connect'
gem 'test-unit', '~> 3.0'

group :development, :test do
#  gem 'sqlite3'
  gem 'pg'
  gem 'test-unit', '~> 3.0'
  gem 'puma'
end

group :test do
  gem 'turn', :require => false
end

group :production do
  gem 'pg'
  gem 'rack-ssl', :require => 'rack/ssl'
end