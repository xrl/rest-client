source "https://rubygems.org"

if !!File::ALT_SEPARATOR
  gemspec :name => 'rest-client.windows'
else
  gemspec :name => 'rest-client'
end

group :test do
  gem 'irb'
  gem 'rake', '~> 11.0'
  gem 'pry-byebug'
end
