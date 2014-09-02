source 'https://rubygems.org'

gem 'middleman',            '~> 3.3.3'
gem 'middleman-syntax',     '~> 2.0.0'
gem 'middleman-cloudfront'
gem 'middleman-s3_redirect'
gem 'middleman-smusher',    '~> 3.0.0'
gem 'middleman-livereload'
gem 'builder',              '~> 3.2.0'
gem 'redcarpet',            '~> 2.2.2'
gem 'rb-fsevent',           '~> 0.9'
gem 'slim',                 '~> 1.3.8'
gem 'foundation-rails', require: false

group :development, :test do
  gem 'aws-sdk' # For AWS data syncing
  gem 'pry'
end

group :test do
  gem 'rspec' # Unit testing
end

group :production do
  gem 'therubyracer',       '~> 0.11.4'
end
