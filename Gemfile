source 'https://rubygems.org'
require 'json'
require 'open-uri'
versions = JSON.parse(open('https://pages.github.com/versions.json').read)

gem 'github-pages', versions['github-pages']
gem 'jekyll'
gem 'jekyll-assets'
gem 'kramdown'
gem 'bourbon'
gem 'neat'
gem 'foreman'

group :development do
  gem 'guard-livereload', '~> 2.4', require: false
end