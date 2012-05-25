source 'https://rubygems.org'

gem 'rails', '3.0.9'

gem 'jquery-rails', '1.0.14'
gem 'simple_form', '1.5.1'

platform :ruby do
  gem 'mysql2', '~> 0.2.7'
end

platform :mri do
  gem 'unicorn'
end

platform :rbx do
  gem 'puma'
end

platforms :jruby do
  gem 'activerecord-jdbc-adapter'
  gem 'jruby-openssl'
  gem 'jdbc-mysql', :require => false
  gem 'jdbc-sqlite3', :require => false
  gem 'jdbc-postgres', :require => false
  gem 'trinidad'
  gem 'thor'
end
