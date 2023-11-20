source "https://rubygems.org"

gem "jekyll", "~> 4.3.2" # installed by `gem jekyll`

if ENV['JEKYLL_ENV'] == "production"
  gem "just-the-docs", path: "./just-the-docs"
else
  gem "just-the-docs", path: "../just-the-docs"
end
