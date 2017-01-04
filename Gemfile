source 'https://rubygems.org'

gem 'puppet', ENV.key?('PUPPET_VERSION') ? ENV['PUPPET_VERSION'].to_s : '>= 3.8'

gem 'puppetlabs_spec_helper', '>= 0.1.0'
gem 'puppet-lint', '>= 0.3.2'
gem 'facter', '>= 1.7.0'
gem 'facterdb', :git => 'https://github.com/jfryman/facterdb', :ref => 'sles-12-support'
gem 'rspec-puppet-facts', '>= 1.6.0'
gem 'metadata-json-lint'

# json > 2.0.1 is not compatible with Ruby 1.9
if RUBY_VERSION < '2.0.0'
  gem 'json', '< 2'
  gem 'json_pure', '< 2'
end
