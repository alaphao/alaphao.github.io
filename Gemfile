source "https://rubygems.org"

gem "jekyll-theme-hydeout", "~> 4.1"
gem 'jekyll-feed', group: :jekyll_plugins
gem "github-pages", group: :jekyll_plugins 

gem "rake", group: :development

# Windows and JRuby does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.1", :install_if => Gem.win_platform?

