# Jekyll Readme Index

A Jekyll plugin to render a project's README as the site's index.

[![Build Status](https://travis-ci.org/benbalter/jekyll-readme-index.svg?branch=master)](https://travis-ci.org/benbalter/jekyll-readme-index)

## What it does

Let's say you have a GitHub repository with a `README.md` file, that you'd like to use as the index (main page) for a GitHub Pages site. You could rename the file to `index.md`, but then it wouldn't render on GitHub.com. You could add YAML front matter with `permalink: /` to the README, but why force a human to do what Jekyll can automate?

If you have a readme file, and your site doesn't otherwise have an index file, this plugin instructs Jekyll to use the readme as the site's index. That's it. No more, no less.

## Usage

1. Add the following to your Gemfile

  ```ruby
  gem "jekyll-readme-index"
  ```

2. Add the follow to your site's config

  ```yml
  gems:
    - jekyll-readme-index
  ```
