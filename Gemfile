source 'https://rubygems.org'

gem 'rails', '4.0.0'

gem 'pg'

# New gem releases aren't being done. master is newer and supports Rails > 3.0
gem 'acts_as_versioned', :git => 'git://github.com/technoweenie/acts_as_versioned.git'
gem 'charlock_holmes'
gem 'dynamic_form'
gem 'exception_notification'
gem 'fancybox-rails', '>= 0.2.1'
gem 'foundation-rails', '>= 5.2.1.0'
gem 'jquery-rails', '~> 3.0.4'
gem 'jquery-ui-rails', '>= 4.1.0'
gem 'json', '>= 2.3.0'
gem 'mahoro'
gem 'memcache-client'
gem 'net-http-local', :platforms => [:ruby_18, :ruby_19]
gem 'net-purge'
gem 'rack'
gem 'rack-utf8_sanitizer', '>= 1.2.3', :platforms => [:ruby_19, :ruby_20, :ruby_21]
gem 'rake', '0.9.2.2'
gem 'rails-i18n'
gem 'recaptcha', '~> 0.3.1', :require => 'recaptcha/rails'
# :require avoids "already initialized constant" warnings
gem 'rmagick', :require => 'RMagick'
gem 'ruby-msg', '~> 1.5.0',  :git => 'git://github.com/mysociety/ruby-msg.git'
gem 'secure_headers'
gem "statistics2", "~> 0.54"
gem 'syslog_protocol'
gem 'thin'
gem 'vpim'
gem 'will_paginate'
# when 1.2.9 is released by the maintainer, we can stop using this fork:
gem 'xapian-full-alaveteli', '~> 1.2.9.5'
gem 'xml-simple', :require => 'xmlsimple'
gem 'zip'

# Gems related to internationalisation
gem 'fast_gettext'
gem 'gettext_i18n_rails'
gem 'gettext'
gem 'globalize3', :git => 'git://github.com/globalize/globalize.git', :ref => '5fd95f2389dff1'
gem 'locale'
gem 'routing-filter'
gem 'unicode'
gem 'unidecoder'

group :assets do
  gem 'bootstrap-sass'
  gem 'sass-rails', '~> 4.0.0'
  gem 'compass-rails', '2.0.0'
  gem 'coffee-rails', '~> 4.0.0'
  gem 'uglifier', '>= 1.0.3'
  gem 'therubyracer'
end

group :production do
  gem 'newrelic_rpm'
end

group :test do
  gem 'fakeweb'
  gem 'coveralls', :require => false
  gem 'webrat'
  gem 'nokogiri'
end

group :test, :development do
  gem 'factory_girl_rails', '~> 1.7', '>= 1.7.0'
  gem 'rspec-rails', '>= 2.13.2'
  gem 'spork-rails', '>= 4.0.0'
end

group :development do
  gem 'capistrano'
  gem 'mailcatcher'
  gem 'quiet_assets', '>= 1.0.2'
  gem 'rdoc', '>= 4.3.0'
end

group :debug do
  gem 'ruby-debug', :platforms => :ruby_18
  gem 'debugger', :platforms => :ruby_19
  gem 'annotate'
end

