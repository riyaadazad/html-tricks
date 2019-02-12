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
It is totally fine to use a theme for your website, but make sure that you are legally allowed to. There are tons of free site themes on the web, but for this exercise we will be looking for "static" HTML themes, because the programs we will use later to generate the site only work with static sites (for more on that, see "The Strange Case of Dr. Jekyll" below). 

For the HTML-Tricks website, I used the theme called [Telephasic](https://html5up.net/telephasic) from a designer called "[AJ](http://twitter.com/ajlkn)" who is the author of "[HTML5 UP!](https://html5up.net/)". _HTML5 UP!_ "makes spiffy HTML5 site templates that are: Fully Responsive, Built on intelligent HTML5 + CSS3, Super Customizable, 100% Free under the [Creative Commons](https://html5up.net/license)." I recommend _HTML5 UP!_ themes because they look great, and they are basically free to use, as long as you include the license somewhere in your site files and explicitly state that they created the design. Again, you could use any HTML site theme that you have access to, or you could create your own (see "Build-a-Jekyll Workshop" below).

## Introducing GitHub Pages
In this section, I will assume that you have obtained some sort of HTML site that you are legally allowed to use. Now is the part where you decide how to host your site. There are many different ways to do this, and most involve extreme saddening of your wallet. However, there are ways to host your site for free. Enter [GitHub Pages](https://pages.github.com/), a project created by the development platform [GitHub](https://github.com/). It is marketed as "Websites for you and your projects. Hosted directly from your GitHub repository. Just edit, push, and your changes are live."  It's powered by a program called [Jekyll](https://jekyllrb.com/) (for more on that, see "The Strange Case of Dr. Jekyll" below), that allows you to "Transform your plain text into static websites and blogs." 

According to [GitHub Help](https://help.github.com/articles/what-is-github-pages/), GitHub Pages is a static site hosting service designed to host your personal, organization, or project pages directly from a GitHub repository. You can create and publish GitHub Pages sites online using the Jekyll Theme Chooser. Or if you prefer to work locally, you can use GitHub Desktop or the command line. GitHub Pages is a static site hosting service and doesn't support server-side code such as, PHP, Ruby, or Python....GitHub Pages sites are publicly available on the internet, even if their repositories are private. If you have sensitive data in your Page repository, you may want to remove it before publishing....GitHub Pages sites shouldn't be used for sensitive transactions like sending passwords or credit card numbers. Your use of GitHub Pages is subject to the GitHub Terms of Service, including the prohibition on reselling....GitHub Pages is not intended for or allowed to be used as a free web hosting service to run your online business, e-commerce site, or any other website that is primarily directed at either facilitating commercial transactions or providing commercial software as a service (SaaS)....Warning: If the URL for your GitHub Pages site contains a username or organization name that begins or ends in a dash, or contains consecutive dashes, then people browsing with Linux will receive a server error when they visit the site. To fix this, change your GitHub username to remove non-alphanumeric characters."

Take note that "Published GitHub Pages sites may be no larger than 1 GB." However, unless you publish a lot of local videos to your blog, this will likely not be an issue. You can always use YouTube, and if you are worried about your video being "out there", you can upload it as "unlisted" so that only people with the exact link will be able to view it. You can also insert your video into a Google Slides, then publish your Google Slides and embed _that_ into your site.

Of course, the catch is that your site will have a subdomain, such as "your-GitHub-username.github.io/". This can work in your favor if you intend for your site to based on topics like technology, since GitHub is an industry-recognized product. If you prefer to not have your site domain with GitHub, you can check out other alternatives to GitHub Pages for free hosting, such as [Netlify](https://www.netlify.com/), which is "An all-in-one workflow that combines global deployment, continuous integration, and automatic HTTPS. And that’s just the beginning." Sites published for free with Netlify will have a subdomain of "your-site-name.netlify.com". GitHub Pages and Netlify are conceptually similar, but since I am more familiar with GitHub Pages, so I will be using that in this article. (And many of the terms and restrictions that I sourced from GitHub Help also apply to Netlify.)

As a last resort, you can always pay for a cheap domain from [GoDaddy](https://www.godaddy.com/) and host your GitHub Pages using a custom domain (but that would defeat the purpose of this article, right?).

Anyway, the way GitHub Pages works is that it uses your GitHub account username as the site name ("username.github.io"), so be sure to use an appropriate name. Although, if you desperately want to use a funny username, you can also create an organization page (see "GitHub User vs. Organization vs. Project Pages" below). 

For now, let's say that you are using your GitHub username to create your site from scratch. To do this, navigate to [github.com](https://github.com/) and sign in. Next, you'll need to create a new "repository" (which is developer lingo for a project folder with code) by clicking on any of those "New" buttons (at the time of writing, these buttons are green). You can also click the plus "+" sign at the top, and then clicking on "New repository". From there, you'll be able to name your repository.

## GitHub User vs. Organization vs. Project Pages

Let's take a quick break and explain the difference between GitHub User, Project, and Organization pages. Please note that this section is a quick introduction, and since things could change later, please refer to the official full article from GitHub Help on User, Organization, and Project Pages [here](https://help.github.com/articles/user-organization-and-project-pages/). According to GitHub Help, "There are two basic types of GitHub Pages sites: Project Pages sites, and User and Organization Pages sites. They are nearly identical but have some important differences." 

Basically, GitHub User pages are like a personal homepage, where you can put anything you'd like, and it would be accessible at "github-username.github.io". A GitHub Organization page is the same concept, except for an organization that you own (you can create as many organizations under your GitHub username as you'd like, and from that you could create as many "site-name.github.io" sites as you please). A GitHub project page is a site that lives specifically in the project repository, or folderof code. It's link would be "github-name.github.io/project-repository-name", where "github-name" could be either your username or the name of an organization that you create. It's your choice, and in this article we'll try to cover those scenarios. 

## The Strange Case of Dr. Jekyll

<!-- from Intro'ing GitHub Pages -->
<!-- jekyll only works with static sites as mentioned in a previous section -->


## Build-a-Jekyll Workshop

<!-- you can create your own Jekyll theme, but that is over the scope of this article. we can generate minima or convert an HTML theme -->
