source 'https://rubygems.org'

# Jekyll 4.x. The `github-pages` gem used to be pinned here, which forced
# Jekyll 3.10 and a frozen set of transitive dependencies. Deployment now
# builds from this Gemfile too (see .github/workflows/jekyll-gh-pages.yml),
# so local and CI stay on the same versions.
gem 'jekyll', '~> 4.4'

group :jekyll_plugins do
  gem 'jekyll-feed', '~> 0.17'
  gem 'jekyll-gist', '~> 1.5'
  gem 'jekyll-seo-tag', '~> 2.9'
  gem 'jemoji', '~> 0.13'
end

# No longer default gems on modern Ruby, but still required at runtime.
gem 'csv', '~> 3.3'
gem 'base64', '~> 0.2'
gem 'bigdecimal', '~> 3.1'
gem 'webrick', '~> 1.9'
