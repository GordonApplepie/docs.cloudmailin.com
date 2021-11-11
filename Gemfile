source 'https://rubygems.org'

# Generating
gem 'nanoc'
gem 'commonmarker'
gem "haml", '~> 5.0'
gem "sass"
gem 'nanoc-sprockets3', require: 'nanoc-sprockets'
gem 'bootstrap-sass', '~> 3.4'
gem "builder"
gem 'rouge'
gem 'ruby-jq', '~> 0.1', require: 'jq'
gem 'nokogiri'

# Versions before this have potential security issue although it doesn't affect us really
# it's better not to install vulnerable versions.
gem "yajl-ruby", ">= 1.3.1"

group :developement do
  gem 'rake'
  gem 'fog-aws'
  gem 'adsf'
  gem 'adsf-live'
  gem 'guard-nanoc'
  gem 'mime-types'
  gem 'w3c_validators'
end

group :vscode do
  # VSCode
  gem 'debase'
  gem 'rubocop'
  gem 'ruby-debug-ide'
  gem 'solargraph'
end
