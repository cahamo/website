source "https://rubygems.org"

gem "github-pages", "~> 225", group: :jekyll_plugins

gem "activesupport", ">= 6.0.3.1" # fix security issue

gem "jekyll-redirect-from"

# If you have any plugins, put them here!
#group :jekyll_plugins do
#end

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?

# Vulnerability issues
gem "addressable", ">= 2.8.0"
gem "nokogiri", ">= 1.13.6"
