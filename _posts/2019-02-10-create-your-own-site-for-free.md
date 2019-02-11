---
published: false
layout: right-sidebar
description: Anything is possible with the power of Jekyll and GitHub Pages!
permalink: /how-to-create-your-own-blog-for-free
image: 'http://www.thebluediamondgallery.com/wooden-tile/images/website.jpg'
image-alt-text: Scrabble tiles spelling out the word website
image-link: 'http://www.thebluediamondgallery.com/wooden-tile/images/website.jpg'
---
Creating a new site can be exciting. No matter what you need a site for, whether you are a student looking to impress future schools and employers with a personal blog, or an established professional trying to share your knowledge with others, this article is for you. In this post, I will walk you through how I created this HTML-Tricks blog site, and how you can do it too. 

## Planning Makes Perfect
The first step before beginning anything is to plan it out, and this applies especially to websites. It is not necessary to make your wallet cry by utilizing a design studio like the products offered by [Adobe](https://www.adobe.com/). If you know HTML and CSS already, then good for you. But for others, it may simply be too time consuming to create a site from scratch, and that is where theming comes in. 

## To Theme or Not to Theme?
It is totally fine to use a theme for your website, but make sure that you are legally allowed to. There are tons of free site themes on the web, but for this exercise we will be looking for "static" HTML themes, because the programs we will use later to generate the site only work with static sites (more on that later). 

For the HTML-Tricks website, I used the theme called [Telephasic](https://html5up.net/telephasic) from a designer called "[AJ](http://twitter.com/ajlkn)" who is the author of "[HTML5 UP!](https://html5up.net/)". _HTML5 UP!_ "makes spiffy HTML5 site templates that are: Fully Responsive, Built on intelligent HTML5 + CSS3, Super Customizable, 100% Free under the [Creative Commons](https://html5up.net/license)." I recommend _HTML5 UP!_ themes because they look great, and they are basically free to use, as long as you include the license somewhere in your site files and explicitly state that they created the design. Again, you could use any HTML site theme that you have access to, or you could create your own (later).

## Introducing GitHub Pages
In this section, I will assume that you have obtained some sort of HTML site that you are legally allowed to use. Now is the part where you decide how to host your site. There are many different ways to do this, and most involve extreme saddening of your wallet. However, there are ways to host your site for free. Enter [GitHub Pages](https://pages.github.com/), a project created by the development platform [GitHub](https://github.com/). It is marketed as "Websites for you and your projects. Hosted directly from your GitHub repository. Just edit, push, and your changes are live." The way GitHub Pages works is that it is powered by a program called [Jekyll](https://jekyllrb.com/) (more on that below), that allows you to "Transform your plain text into static websites and blogs." Of course, the catch is that your site will have a subdomain, such as "your-GitHub-username.github.io/". This can work in your favor if you intend for your site to based on topics like technology, since GitHub is an industry-recognized product. If you prefer to not have your site domain with GitHub, you can check out other alternatives to GitHub Pages for free hosting, such as [Netlify](https://www.netlify.com/), which is "An all-in-one workflow that combines global deployment, continuous integration, and automatic HTTPS. And that’s just the beginning." Sites published for free with Netlify will have a subdomain of "your-site-name.netlify.com". GitHub Pages and Netlify are conceptually similar, but since I am more familiar with GitHub Pages, so I will be using that in this article.

## The Strange Case of Dr. Jekyll