source "https://rubygems.org"

# Hello! This is where you manage which Jekyll version is used to run.
# When you want to use a different version, change it below, save the
# file and run `bundle install`. Run Jekyll with `bundle exec`, like so:
#
#     bundle exec jekyll serve
#
# This will help ensure the proper Jekyll version is running.
# Happy Jekylling!
# gem "jekyll", ">= 3.8.4"

# This is the default theme for new Jekyll sites. You may change this to anything you like.
gem "minima", "~> 2.5"

# If you want to use GitHub Pages, remove the "gem "jekyll"" above and
# uncomment the line below. To upgrade, run `bundle update github-pages`.
# If you have any plugins, put them here! Grouping plugins ensures proper autoloading by Jekyll.

if RUBY_ENGINE == "jruby"
  # Local JRuby 10 / Ruby 4 development
  gem "jekyll", "~> 3.10.0"

  group :jekyll_plugins do
    gem "jekyll-feed", "~> 0.17.0"
    gem "jekyll-seo-tag", "~> 2.8.0"
    gem "jekyll-redirect-from", "~> 0.16.0"

    # Included by github-pages 232
    gem "jekyll-paginate", "1.1.0"
  end

  # GitHub Pages 232 uses this Markdown parser.
  gem "kramdown-parser-gfm", "1.1.0"

  # 0.7/0.8 no longer have the old JRuby Java package.
  gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]

  # Needed because JRuby 10 runs with Ruby 4.0 stdlib packaging, 
  # while Jekyll 3.x / safe_yaml assume these are available. 
  gem "base64" 
  gem "csv" 
  gem "bigdecimal"

else
  # GitHub Pages build environment
  gem "github-pages", "~> 232"
end

# Windows does not include zoneinfo files, so bundle the tzinfo-data gem
gem "tzinfo-data", "~> 1.2026.3", platforms: %i[windows jruby]

# Performance-booster for watching directories on Windows (MRI only; restricted to C-extension platforms so JRuby skips compilation)
gem "wdm", "~> 0.2.0", platforms: %i[mingw x64_mingw]

gem "webrick", "~> 1.9.2"
