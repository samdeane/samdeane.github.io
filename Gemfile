source "https://rubygems.org"

# Match GitHub Pages' Jekyll version with independently patched dependencies.
gem "jekyll", "~> 3.10.0"
gem "kramdown", "~> 2.4"
gem "kramdown-parser-gfm", "~> 1.1"

# Ruby 3.4 supplies these safe_yaml and Liquid dependencies as separate gems.
gem "base64", "~> 0.3"
gem "bigdecimal", "~> 3.3"

group :jekyll_plugins do
  # Preserve GitHub Pages' metadata and Markdown processing defaults.
  gem "jekyll-github-metadata", "~> 2.16"
  gem "jekyll-relative-links", "~> 0.6"
  gem "jekyll-optional-front-matter", "~> 0.3"
  gem "jekyll-readme-index", "~> 0.3"
  gem "jekyll-default-layout", "~> 0.1"
  gem "jekyll-titles-from-headings", "~> 0.5"
  gem "jekyll-paginate", "~> 1.1"
end
