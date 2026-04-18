# gunion.pl website

This repository contains the website for http://gunion.pl

## Developing locally

Follow these steps to build and view your changes locally:

1. Install `ruby` and `bundler`
2. Check out the repository 
3. `cd docs/`
4. Configure bundler to install locally:

   `bundle config set --local path 'vendor/bundle'`

5. Install all the ruby dependencies with `bundle install`
6. Run local server with `JEKYLL_ENV=production bundle exec jekyll serve --livereload`
