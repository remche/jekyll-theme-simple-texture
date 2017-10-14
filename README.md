# Simple Texture Jekyll Theme


Simple Texture is a gem-based responsive simple texture styled Jekyll theme for [Jekyll][Jekyll] 3.3 or above,
which can also be forked as a boilerplate for older versions of Jekyll.


1. Fork the repo [here](https://github.com/yizeng/jekyll-theme-simple-texture#fork-destination-box)

2. Clone the repo just forked.

       git clone git@github.com:[YOUR_USERNAME]/jekyll-theme-simple-texture.git

3. Delete `starter-kit` folder and `jekyll-theme-simple-texture.gemspec` file (they're for people installing via gem)

4. Install Bundler if haven't done so.

       gem install bundler

5. Update the `Gemfile` to look like the following:

   ```ruby
   source "https://rubygems.org"

   gem 'jekyll', '= 3.5.2' # locked in to be consistent GitHub Pages.

   group :jekyll_plugins do
     gem 'jekyll-feed'
     gem 'jekyll-redirect-from'
     gem 'jekyll-seo-tag'
     gem 'jekyll-sitemap'
   end
   ```

6. Run `bundle install` to install dependencies.

7. Run Jekyll with `bundle exec jekyll serve`

8. Hack away at <http://localhost:4000>!
