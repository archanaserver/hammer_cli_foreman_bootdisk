source "https://rubygems.org"

gemspec

gem 'rake'
# for generating i18n files, gettext > 3.0 dropped ruby 1.8 support
gem 'gettext', '~> 2.0'

# load local gemfile
local_gemfile = File.join(File.dirname(__FILE__), 'Gemfile.local')
self.instance_eval(Bundler.read_file(local_gemfile)) if File.exist?(local_gemfile)
