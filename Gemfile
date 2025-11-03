# frozen_string_literal: true

source "https://rubygems.org"

gem "rails", "8.1.1"
gem "propshaft"
gem "pg"
gem "puma"
gem "importmap-rails"
gem "turbo-rails"
gem "stimulus-rails"
gem "jbuilder"

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", platforms: [:windows, :jruby]

# Reduces boot times through caching; required in config/boot.rb
gem "bootsnap", require: false

# Add HTTP asset caching/compression and X-Sendfile acceleration to Puma [https://github.com/basecamp/thruster/]
gem "thruster", require: false

gem "rails_pulse"
gem "sshkit", require: false

group :development, :test do
  gem "bundler-audit", require: false
  gem "brakeman", require: false
end

group :development do
  gem "license_finder", require: false
  gem "rubocop", require: false
  gem "rubocop-disable_syntax", require: false
  gem "rubocop-performance", require: false
  gem "rubocop-rails", require: false
  gem "rubocop-rspec", require: false
  gem "rubocop-rspec_rails", require: false
  gem "fasterer", require: false
  gem "standard", "1.51.1", require: false
end
