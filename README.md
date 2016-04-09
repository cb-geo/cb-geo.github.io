# CB-Geo webpage
> Krishna Kumar

Based on [**So Simple Theme**](http://mmistakes.github.io/minimal-mistakes/)

## Pre-requisites

* ruby > 2.0

* ruby-devel

* rubygem-bundler

* zlib zlib-devel zlib-static

## Getting Started

* bundle update

* bundle exec jekyll build --incremental

* bundle exec jekyll serve --watch

* Point your browser to localhost:4000

## HTML-Proofer test
  - set -e
  - bundle exec jekyll build --drafts
  - bundle exec htmlproof ./_site
