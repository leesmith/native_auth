source "https://rubygems.org"

ruby file: ".ruby-version"

gem "bcrypt", "~> 3.1.7"
gem "bootsnap", require: false
gem "image_processing", "~> 2.2"
gem "importmap-rails"
gem "jbuilder"
gem "kamal", require: false
gem "propshaft"
gem "puma"
gem "rails"
gem "solid_cable"
gem "solid_cache"
gem "solid_queue"
gem "sqlite3"
gem "stimulus-rails"
gem "tailwindcss-rails"
gem "thruster", require: false
gem "turbo-rails"

group :development, :test do
  gem "brakeman", require: false
  gem "bundler-audit", require: false
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"
  gem "rubocop-rails-omakase", require: false
end

group :development do
  gem "web-console"
end

group :test do
  gem "capybara"
  gem "selenium-webdriver"
end
