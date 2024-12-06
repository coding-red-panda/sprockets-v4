# Ruby on Rails - Sprockets v4

This project is a simply dummy project to test the configuration of the `sprockets` v4 pipeline
using the following extra plugins:

* coffeescript
* erb templating in assets

The goal is to determine the correct configuration to make the pipeline work
and compile assets correctly when coming from a `sprockets` v3 setup.

## Setup

* `rails new --skip-docker --asset-pipeline=sprockets --css=sass .`
* add the `coffee-rails` gem
* `bundle install`

The assets are included in the application based on the existing production examples.
When running `assets:precompile` the correct output should be generated in the `public/assets` folder.
