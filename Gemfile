source "https://rubygems.org"

gem "rails", "3.2.13"
gem 'mysql2', '0.3.11'

gem "email_signup", path: "engines/email_signup"
gem "teaser", path: "engines/teaser"
gem "annoyance", path: "gems/annoyance"

group :test, :development do
  gem "rspec-rails", "2.12.2"
  gem "capybara", "1.1.4"

  #Development requirements of teaser engine (for travis-ci)
  gem "shoulda-matchers", "1.4.2"
  gem "poltergeist", "1.0.2"
  gem "jasmine", "1.3.1"
end