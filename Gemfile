source "https://rubygems.org"

ruby file: ".ruby-version"

gem "rails", "~> 7.2.3"
gem "sqlite3", ">= 2.1", group: [:development, :test]
gem "pg", "~> 1.1", group: :production
gem "puma", ">= 5.0"
gem "image_processing", "~> 1.2"

group :development, :test do
  gem "debug", platforms: %i[ mri windows ], require: "debug/prelude"
  gem "brakeman", require: false
  gem "rubocop-rails-omakase", require: false
end

group :development do
  gem "web-console"
end

gem "importmap-rails", "~> 2.1"
