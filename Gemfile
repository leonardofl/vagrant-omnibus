source 'https://rubygems.org'

gemspec

group :development do
  # We depend on Vagrant for development, but we don't add it as a
  # gem dependency because we expect to be installed within the
  # Vagrant environment itself using `vagrant plugin`.
  gem 'vagrant', git: 'git://github.com/mitchellh/vagrant.git', tag: 'v1.6.4'
  gem 'vagrant-windows', '~> 1.6.0'
end

group :acceptance do
  gem 'vagrant-digitalocean', '~> 0.5'
  gem 'vagrant-aws', '~> 0.4'
  gem 'vagrant-rackspace', '~> 0.1'
end

group :docs do
  gem 'yard', '~> 0.8'
  gem 'redcarpet', '~> 2.2'
  gem 'github-markup', '~> 0.7'
end
