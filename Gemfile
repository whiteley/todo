source 'https://rubygems.org'

gem 'rails', '~> 3.0.9'

gem 'jquery-rails', '1.0.14'
gem 'simple_form', '1.5.1'

platforms :ruby do
  gem 'mysql2', '~> 0.2.7'
  gem 'pg', '~> 0.13.2'
  gem 'sqlite3'
end

platforms :mri do
  gem 'unicorn'
end

platforms :rbx do
  gem 'puma'
end

platforms :jruby do
  gem 'activerecord-jdbc-adapter'
  gem 'jdbc-mysql', :require => false
  gem 'jdbc-postgres', :require => false
  gem 'jdbc-sqlite3', :require => false
  gem 'jruby-openssl'
  gem 'thor'
  gem 'trinidad'
end
