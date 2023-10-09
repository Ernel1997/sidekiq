source "https://rubygems.org"

gemspec

gem "rake"
gem "redis-namespace", github: "resque/redis-namespace", branch: :master
gem "rails", ">= 7.1.0"
gem "sqlite3", platforms: :ruby
gem "activerecord-jdbcsqlite3-adapter", platforms: :jruby

group :test do
  gem "minitest"
  gem "simplecov"
  gem "codecov", require: false
end

group :development, :test do
  gem "standard"
end

group :load_test do
  gem "hiredis"
  gem "toxiproxy"
end
