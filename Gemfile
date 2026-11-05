source "https://rubygems.org"

# github-pages includes Jekyll and all plugins GitHub Pages supports
group :jekyll_plugins do
  gem "github-pages"
  gem "jekyll-remote-theme"
  gem "jekyll-seo-tag"
end

# Windows and JRuby do not include zoneinfo files
platforms :mingw, :x64_mingw, :mswin, :jruby do
  gem "tzinfo", ">= 1", "< 3"
  gem "tzinfo-data"
end

# Performance booster for watching directories on Windows
gem "wdm", "~> 0.1", platforms: [:mingw, :x64_mingw, :mswin]

# Lock http_parser.rb on JRuby (newer versions lack a Java counterpart)
gem "http_parser.rb", "~> 0.6.0", platforms: [:jruby]

# Needed for `jekyll serve` on Ruby 3+
gem "webrick", "~> 1.8"
