# TitaniumCasts

This is the source code for a new site that I'm annoucing soon. It is totally based (and all credits should be given to) the RailsCasts source code, and the amazing job of Ryan Bates. See more about RailsCasts below.

## RailsCasts

Please [let him know](https://github.com/inbox/new/ryanb) if you plan to use his app for your site.

## Setup

This is designed to run on Ruby 1.9.3 or higher. If you're using [RVM](http://rvm.beginrescueend.com/) it should automatically switch to 1.9.3 when entering the directory.

Run `script/setup`. This will generate the config files, install gems, and migrate the database.

You can then start the server with `rails s` and run the specs with `rake`.

You may want to install [Sphinx](http://sphinxsearch.com/), run the index and start rake commands, and set `thinking_sphinx: true` in `app_config.yml`. This isn't required since it will default to a primitive search.
