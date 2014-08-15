# hexo-theme-athena

A theme for [hexo](http://hexo.io/), modify from Hexo default [landscape](https://github.com/hexojs/hexo-theme-landscape/) theme.

## Installation

### Install

``` bash
$ git clone https://github.com/steven5538/hexo-theme-athena.git themes/athena
```

### Enable

Modify `theme` setting in `_config.yml` to `athena`.

### Update

``` bash
cd theme/athena
git pull
```

## Configuration

``` yml
# Header
menu:
  Home: /
  Archives: /archives
  About: /about
# Header Icon
menu_icon:
  Home: nav-home-icon
  Archives: nav-archives-icon
  About: nav-about-icon

rss: /atom.xml

# Content
excerpt_link: Read More
fancybox: true

# Miscellaneous
google_analytics:
favicon: /favicon.png
twitter:
google_plus:
fb_admins:
fb_app_id:
```

- **menu** - Navigation menu, you need to `hexo new page 'about'` for the about page.
- **menu_icon** - Navigation icon
- **rss** - RSS link
-- **excerpt_link** - "Read More" link at the bottom of excerpted articles. `false` to hide the link.
- **fancybox** - Enable [Fancybox]
- **google_analytics** - Google Analytics ID
- **favicon** - Favicon path
- **twitter** - Twiiter ID
- **google_plus** - Google+ ID