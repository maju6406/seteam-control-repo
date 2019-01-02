source 'https://rubygems.org'

case RUBY_PLATFORM
when /darwin/
  gem 'CFPropertyList'
end

gem 'puppet'
gem 'puppetlabs_spec_helper', '>= 2.12.0'
gem 'semantic_puppet'
gem 'ra10ke'
gem 'rubocop'
gem 'rubocop-rspec'
gem 'rest-client'
gem 'facter', '2.4.6'
gem 'r10k', '>= 2.5.5'
gem 'hiera-eyaml', '~> 2.1'

group :development, :unit_tests do
  gem 'metadata-json-lint'
  gem 'rspec-puppet-facts', :git => 'https://github.com/mcanevet/rspec-puppet-facts.git',
                      :ref => 'fe21de12108fbab0123bdc4db2365a29ea62f171'
  gem 'puppet-blacksmith', '>= 4.1.2'
  gem 'simplecov'
  gem 'simplecov-console'
  gem 'rspec-puppet', :git => 'https://github.com/rodjek/rspec-puppet.git',
                      :ref => 'eaba657a8e876c8c4a881a6d47df76cfdda62b3f'
  gem 'puppet-syntax', '>= 2.4.0'
  gem 'parallel_tests'
  gem 'json_pure', '<= 2.0.1' if RUBY_VERSION < '2.0.0'
end


group :system_tests do
  gem 'serverspec'
end

