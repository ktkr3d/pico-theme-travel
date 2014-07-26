# Travel - Theme for Pico CMS

## Installation

``` bash 
$ cd themes
$ git clone git@github.com:ktkr3d/pico-theme-travel.git
$ tree -d
.
├── default
│   └── scripts
└── pico-theme-travel
    └── assets
        ├── css
        ├── img
        └── js
            └── libs
```

## Configuration

Edit config.php

``` php
// Change
$config['site_title'] = 'your site title';
$config['theme'] = 'pico-theme-travel';

// Add
$config['theme_travel_site_description'] = 'site description';
$config['theme_travel_site_auther'] = 'site auther';
$config['theme_travel_tags_enable'] = 'false'; // https://github.com/szymonkaliski/Pico-Tags-Plugin
$config['theme_travel_twitter_enable'] = 'false';
$config['theme_travel_twitter_account'] = 'twitter account';
$config['theme_travel_google_plus_enable'] = 'false';
$config['theme_travel_google_plus_account'] = 'google+ account';
$config['theme_travel_rss_enable'] = 'false'; // https://github.com/gilbitron/Pico-RSS-Plugin
$config['theme_travel_pagination_enable'] = 'false'; // https://github.com/rewdy/Pico-Pagination
$config['theme_travel_disqus_enable'] = 'true';
$config['theme_travel_disqus_short_name'] = 'disqus short name';
$config['theme_travel_site_fqdn_path'] = 'foo.bar.com';
```

## About Travel Theme for Pico CMS

Inspired from
- Movable Type
- Wordpress
- Octopress
- PukiWiki
