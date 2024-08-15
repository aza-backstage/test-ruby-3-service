# frozen_string_literal: true

source "https://rubygems.org"

# Bundle edge Rails instead: gem "rails", github: "rails/rails", branch: "main"
gem "rails", "~> 7.1.3", ">= 7.1.3.4"

group :development do
  gem "better_errors"
  gem "binding_of_caller"
  gem "letter_opener"
  gem "ruby-prof"
  gem "spring"
  gem "web-console"
end

group :test do
  gem "capybara-screenshot"
  gem "net_http_ssl_fix"
  gem "rspec"
  gem "rspec_api_documentation"
  gem "rspec-rails"
  gem "shoulda-matchers"
  gem "simplecov"
  gem "timecop"
  gem "webmock", require: "webmock/rspec"
  gem "yardstick"
end

group :development, :test do
  gem "brakeman"
  gem "bundler-audit"
  gem "capybara"
  gem "factory_bot_rails"
  gem "listen"
  gem "parallel_tests"
  gem "pry"
  gem "pry-byebug"
  gem "pry-rails"
  gem "rb-readline"
  gem "rubocop", require: false
  gem "rubocop-capybara", require: false
  gem "rubocop-factory_bot", require: false
  gem "rubocop-performance", require: false
  gem "rubocop-rails", require: false
  gem "rubocop-rake", require: false
  gem "rubocop-rspec", require: false
  gem "rubocop-thread_safety", require: false
  gem "unicorn-rails"
end

# External Gems
gem "aasm"
gem "active_model_serializers"
gem "analytics-ruby", require: "segment"
gem "approval"
gem "attr_encrypted"
gem "authlogic"
gem "autotuner"
gem "aws-sdk"
gem "bcrypt"
gem "blockcypher-ruby", require: "blockcypher"
gem "bootsnap", require: false
gem "bootstrap-sass"
gem "bootstrap-select-rails"
gem "caxlsx"
gem "caxlsx_rails"
gem "coffee-rails"
gem "dalli", "3.2.6"
gem "dalli-elasticache"
gem "dotenv-rails", require: "dotenv/load"
gem "ejs"
gem "elasticsearch"
gem "font-awesome-rails"
gem "google-authenticator-rails"
gem "honeybadger"
gem "i18n-js"
gem "iso_country_codes"
gem "jquery-rails"
gem "jquery-validation-rails"
gem "kaminari"
gem "kgio"
gem "kt-paperclip"
gem "lograge-sql"
gem "money-rails"
gem "net-protocol"
gem "optimizely-sdk"
gem "paper_trail"
gem "paper_trail-association_tracking"
gem "paper_trail-globalid"
gem "pg"
gem "pg_search"
gem "postgresql_cursor"
gem "puma"
gem "rack-attack"
gem "rack-cors", require: "rack/cors"
gem "rails-controller-testing"
gem "redis-namespace"
gem "ruby-saml"
gem "sass-rails"
gem "scanf"
gem "scrypt"
gem "select2-rails"
gem "sidekiq", "~> 6.5"
gem "sidekiq-scheduler"
gem "sidekiq-status"
gem "silencer", require: false
gem "skim"
gem "sprockets-rails"
gem "sucker_punch"
gem "thwait"
gem "uglifier"
gem "unicorn"
gem "uuid"
gem "virtus"
gem "with_advisory_lock"
gem "xmlrpc"

# aza-siem must be last gem to load in order to detect dependencies and let dotenv load ENVs
gem "aza-siem", git: "git@github.com:aza-backstage/aza-siem.git"
