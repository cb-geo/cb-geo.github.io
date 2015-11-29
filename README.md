# Jekyll3-Base Template
> Krishna Kumar

Based on [**So Simple Theme**](http://mmistakes.github.io/minimal-mistakes/)

## Getting Started

* bundle exec jekyll build --incremental

* bundle exec jekyll serve --watch

* Point your browser to localhost:4000

## HTML-Proofer test
  - set -e
  - bundle exec jekyll build --drafts
  - bundle exec htmlproof ./_site
