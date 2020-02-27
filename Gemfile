source "https://rubygems.org"

group :test do
  gem "rake", ">= 12.3.3"
  gem "puppet", ENV['PUPPET_VERSION'] || '~> 3.7.0'
  gem "rspec-puppet"
  gem "puppetlabs_spec_helper", ">= 1.1.1"
  gem "metadata-json-lint"
  gem "rspec-puppet-facts"
end

group :development do
  gem "travis"
  gem "travis-lint"
  gem "vagrant-wrapper"
  gem "puppet-blacksmith"
  gem "guard-rake", ">= 1.0.0"
end

group :system_tests do
  gem "beaker", ">= 2.43.0"
  gem "beaker-rspec", ">= 5.3.0"
end
