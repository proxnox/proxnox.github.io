source "https://rubygems.org"

# Force a version of Jekyll that is stable on Windows 7
gem "jekyll", "4.2.2"

# These are the specific versions that avoid the 'dart.exe' crash
gem "jekyll-sass-converter", "2.2.0"
gem "sassc", "2.4.0"

# Required for Windows 7 stability
gem "wdm", "~> 0.1.1"
gem "webrick"

# Standard plugins used by the TeXt theme
group :jekyll_plugins do
  gem "jekyll-feed", "~> 0.12"
  gem "jekyll-sitemap"
  gem "jekyll-paginate"
  gem "jekyll-seo-tag"
end

# Finally, include the theme itself as a gem
gem "jekyll-text-theme"