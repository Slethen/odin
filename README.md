# Odin-Slethen

[![GitHub version](https://badge.fury.io/gh/Slethen%2Fodin-slethen.svg)](https://badge.fury.io/gh/Slethen%2Fodin-slethen)
![Ghost version](https://img.shields.io/badge/Ghost-1.0.x-brightgreen.svg)
[![Donate](https://img.shields.io/badge/donate-paypal-003087.svg)](https://www.paypal.me/slethenio/5)

> A simple theme for Ghost made for geeks, hackers and developers (forked from Casper).

[<img src="http://i.imgur.com/lxpvkBo.jpg">](https://slethen.io)

***Do you want new features?***  
Feel free to open an issue

## Intro
**Odin-Slethen** is a fork of the [Odin](https://github.com/h4t0n/odin) theme.
I created this fork to change some things I didn't like about Odin and to add compatiblity
with the latest stable version of Ghost 1.0.X

### Features
* Casper minimalistic and clean style (without right side menu)
* Works with Ghost 1.0.X
* Fully responsive (for mobiles and tablets)
* Home Page Navigation Menu Buttons
* Google Analytics (easily configurable by code injection in the admin area)
* [Disqus](https://disqus.com) comments (easily configurable by code injection in the admin area)
* [Prism](http://prismjs.com/) Syntax Highlight (all languages supported)
* [RRSSB](https://github.com/kni-labs/rrssb) Extraordinary Social Sharing Buttons
* [Font Awesome](http://fontawesome.io) home page Social Link Icons (easily configurable by code injection in the admin area)

### Demo
I use this theme for my personal blog at [slethen.io](https://slethen.io).

## Installation
To install this theme download the latest zip from the [releases](https://github.com/Slethen/odin-slethen/releases) page.
Then simply upload it in the Admin Area and activate it.

## Configuration
No need to configure ***Prism*** or ***RRSSB*** buttons.

To add Homepage Navigation Menu Buttons simply add the links in your Navigation Admin Area. They may be useful for static pages (*AboutMe* for example) or for shortcut to your (best) post tags.  

Odin comes with a default ***favicon*** generated with [Real Favicon Generator](http://realfavicongenerator.net). If you want to add your *favicon* you can generate your own (with [Real Favicon Generator](http://realfavicongenerator.net)) and place downloaded files inside the ***assets/img/favicons*** Odin directory.

***Disqus*** comments, ***Google Analytics***  and ***Font Awesome Home Page Social Link Icons*** are disabled by default, but they are easily configurable with *Blog Header Code Injection* inside your Ghost Admin Area.

```html
<script>
// to enable Google Analytics
var ga_id = 'YOUR-UA-ID_HERE';

// to enable Disqus
var disqus_shortname = 'YOUR_DISQUS_SHORTNAME'


// to enable Social Link Icons add the social_link object
// with the pair key/value -> social_network/link
// NB: the key is used to include the right icon from Font Awesome
// (you can include any Font Awesome icon)

// Example1: default social network icons
var social_link = {
    'twitter': 'https://twitter.com/h4t0n',
    'linkedin': 'https://it.linkedin.com/in/andreatarquini',
    'github': 'https://github.com/h4t0n',
    'rss':'https://blog.h4t0n.com/rss/'
    // you can add more icons
}

// Example2: squared social network icons
var social_link = {
    'twitter-square': 'https://twitter.com/h4t0n',
    'linkedin-square': 'https://it.linkedin.com/in/andreatarquini',
    'github-square': 'https://github.com/h4t0n',
    'rss':'https://blog.h4t0n.com/rss/'
    // you can add more icons
}

</script>


```


## Copyright & License

Released under the MIT License.  
Copyright (c) 2017 [Joel Duncan](https://slethen.io)  
Copyright (c) 2016 [Andrea Tarquini](https://blog.h4t0n.com) aka [@h4ton](https://twitter.com/h4t0n)  
Copyright (c) 2013-2015 Ghost Foundation (for Casper theme substantial portions of code)
