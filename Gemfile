source 'http://rubygems.org'

gemspec

if ENV['USE_LOCAL_SPREE']
  gem 'spree_core', :path => '~/code/spree'
else
  gem 'spree', :git => 'git://github.com/spree/spree.git'
end
