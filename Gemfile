source "https://rubygems.org"

gem "jekyll", "~> 4.3"
gem "jekyll-sass-converter", "~> 3.0"

group :jekyll_plugins do
  gem "jekyll-seo-tag", "~> 2.8"
end

# Standard-library gems no longer bundled with recent Ruby versions
gem "base64"
gem "csv"
gem "logger"
gem "webrick", "~> 1.8"

# Windows and JRuby don't include zoneinfo files
platforms :windows, :jruby do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end
