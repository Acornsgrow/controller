source 'http://rubygems.org'
gemspec

unless ENV['TRAVIS']
  gem 'byebug', require: false, platforms: :mri
  gem 'yard',   require: false
end

gem 'minitest',      '~> 5.8'
gem 'hanami-utils',  '~> 0.8', require: false, github: 'hanami/utils',  branch: 'hanami-configuration'
gem 'hanami-router', '~> 0.7', require: false, github: 'hanami/router', branch: '0.7.x'

group :validations do
  gem 'hanami-validations', '~> 0.6', require: false, github: 'hanami/validations', branch: '0.6.x'

  # This is required until dry-validation 0.8 will be out
  gem 'dry-types',                    require: false, github: 'dry-rb/dry-types'
  gem 'dry-logic',                    require: false, github: 'dry-rb/dry-logic'
  gem 'dry-validation',               require: false, github: 'dry-rb/dry-validation'
end

gem 'coveralls', require: false
