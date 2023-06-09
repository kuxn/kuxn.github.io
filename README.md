## Setup

```
bundle init
bundle config set --local path 'vendor/bundle'

bundle add jekyll
bundle exec jekyll new --force --skip-bundle .

# Comment out gem jekyll in Gemfile

bundle add github-pages

# Update Gemfile
gem "github-pages", "~> GITHUB-PAGES-VERSION", group: :jekyll_plugins

bundle install
bundle exec jekyll serve
```

#### References
Using jekyll with bundler: https://jekyllrb.com/tutorials/using-jekyll-with-bundler/

Creating a GitHub Pages site with Jekyll: https://docs.github.com/en/pages/setting-up-a-github-pages-site-with-jekyll/creating-a-github-pages-site-with-jekyll


