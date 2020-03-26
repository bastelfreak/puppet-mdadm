source "https://rubygems.org"

group :test do
  gem "rake"
  gem "puppet", ENV['PUPPET_VERSION'] || '~> 3.7.0'
  gem "rspec-puppet"
  gem "puppetlabs_spec_helper"
  gem "metadata-json-lint", ">= 0.0.11"
  gem "rspec-puppet-facts", ">= 1.6.1"
end

group :development do
  gem "travis", ">= 1.8.2"
  gem "travis-lint", ">= 2.0.0"
  gem "vagrant-wrapper"
  gem "puppet-blacksmith"
  gem "guard-rake"
end

group :system_tests do
  gem "beaker", ">= 3.7.0"
  gem "beaker-rspec", ">= 6.0.0"
end
