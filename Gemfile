source 'https://rubygems.org'

branch = ENV.fetch('SOLIDUS_BRANCH', 'master')
gem 'solidus', github: 'solidusio/solidus', branch: branch

gem 'rails-controller-testing', group: :test
gem 'pg'
gem 'mysql2'

# Provides basic authentication functionality for testing parts of your engine
gem 'solidus_auth_devise', '~> 1.0'

gemspec
