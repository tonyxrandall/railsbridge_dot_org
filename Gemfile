source "https://rubygems.org"

ruby "2.3.1"

gem "rails", "4.2.6"
gem "thin"
gem "haml-rails"
gem "jquery-rails"
gem "font-awesome-rails"
gem "twitter"
gem "tweetstream"
gem "activeresource"
gem "sprockets-rails"

gem "sass-rails"
gem "coffee-rails"
gem "bootstrap-sass"
gem "uglifier"
gem "bourbon"

# Site Tools & Monitoring
gem "sitemap_generator"

group :production do
  gem "newrelic_rpm"
  gem "rails_12factor"
  gem "google-analytics-rails"
end

group :test, :development do
  # Testing
  gem "rspec-rails"
  gem "capybara"
  gem "email_spec"
  gem "shoulda-matchers"

  # Test Tools
  gem "simplecov", :require => false
  gem "timecop"

  # Debugging Tools
  gem "quiet_assets"
  gem "awesome_print"
  gem "pry-byebug"
end

group :development do
  gem "better_errors"
  gem "binding_of_caller"
end
