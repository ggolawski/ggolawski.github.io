source "https://rubygems.org"

# This is the default theme for new Jekyll sites. You may change this to anything you like.
# gem "minima"

# If you have any plugins, put them here!
group :jekyll_plugins do
  gem "github-pages", "~> 206"
  gem "jekyll-feed", "~> 0.13.0"
  gem "jemoji", "~> 0.11.1"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
# and associated library.
install_if -> { RUBY_PLATFORM =~ %r!mingw|mswin|java! } do
  gem "tzinfo", "~> 1.2"
  gem "tzinfo-data"
end

# Performance-booster for watching directories on Windows
gem "wdm", "~> 0.1.0", :install_if => Gem.win_platform?

