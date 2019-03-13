---
published: false
layout: right-sidebar
description: Enhance your plain site with styling
permalink: /learn-css-in-ten-minutes
image: >-
  https://www.maxpixel.net/static/photo/1x/Programming-Program-Source-Code-Code-Javascript-3337044.jpg
image-alt-text: Wordpress Logo
image-link: >-
  https://www.maxpixel.net/static/photo/1x/Programming-Program-Source-Code-Code-Javascript-3337044.jpg
---
## Intro
So you've decided that you want a website. You did the research and you chose a platform such as [Wordpress](https://wordpress.org/) or [GitHub Pages](https://pages.github.com/), which runs on [Jekyll](https://jekyllrb.com/) (although I do prefer [Jekyll over Wordpress](/why-jekyll-is-better-than-wordpress)). You may have used a theme, or you hand coded your own site from scratch. Depending on your situation, you could have a full blown site that you want to customize further to your liking, or you could have a barebones site that is in serious need of style. This post will help you get started adding style to your web pages. It would be awesome if you had a basic understanding of HTML, and if you need to learn or need a refresher, visit my other post on how to [learn HTML in ten minutes](/learn-html-in-ten-minutes).

## CSS Basics
CSS is the abbreviation for "Cascading Style Sheets" - it says what it does and it does what it says. It's main goal is to style plain HTML web pages into stylized web pages. If the plain HTML text is the skeleton of the web page, then the CSS is the skin and makeup of the web page (and the web page would be an individual person amid a country of web pages, called a web site. And each web site is part of a continent of domains: .com, .net, .org, .gov, .io, and more. And each "domain" continent is part of a system, and a galaxy, and a universe, and... let's get back to CSS). And JavaScript (JS) would be the muscles and organs of the web page.

CSS consists of selectors and values. The selector selects the corresponding HTML tag, and the values dictate how to further style the tag/element (most web browsers add basic styling to a web page with no CSS, such as font size and font family). If you were trying to style the main header (h1) tag of a web page to make it have blue text, a yellow background, and a font size of 28 pixels, your CSS code would look like this:

`/*` This is a comment in CSS: the opening comment looks like `/*` and the 