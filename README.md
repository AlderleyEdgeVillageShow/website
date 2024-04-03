# Alderley Edge Village Show

## Develop

Cause was built with [Jekyll](http://jekyllrb.com/) version 3.3.1, but should support newer versions as well.

Install the dependencies with [Bundler](http://bundler.io/):

~~~bash
$ bundle install
~~~

Run `jekyll` commands through Bundler to ensure you're using the right versions:

~~~bash
$ bundle exec jekyll serve
~~~

## SEO Tag

This site uses the [jekyll-seo-tag](https://github.com/jekyll/jekyll-seo-tag) plugin. You should at least set a title in front matter on each page. Have a look at the [project page](https://github.com/jekyll/jekyll-seo-tag) for more options.

## Google Analytics

[Google Analytics](https://www.google.com/analytics/) is a third party website analytics tool. To install:
1. Add your Google Analytics key to `_config.yml`
2. Run your site in production `JEKYLL_ENV=production`. This is the default in CloudCannon and GitHub Pages.

## Donorbox

[Donorbox](https://donorbox.org/) is a third party embeddable donation form for websites. To install:

1. Set up a campaign on Donorbox
2. Copy the embed code from the Dashboard screen
3. Paste it into `donation_embed` in `_config.yml`

## Mailchimp

[Mailchimp](https://mailchimp.com/) is a third party embeddable newsletter for websites. To install:

1. Set up a campaign on Mailchimp
2. Find the embed code for the sign up form
3. Copy the `<form>`'s action url
4. Paste it into `newsletter_action` in `_config.yml`


https://app.taggbox.com/widget/wall/index/138479
