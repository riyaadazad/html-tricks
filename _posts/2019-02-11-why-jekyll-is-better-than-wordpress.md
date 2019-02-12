---
published: false
layout: right-sidebar
description: 'KISS Wordpress goodbye - Jekyll Keeps It Simple, Stupid'
permalink: /why-jekyll-is-better-than-wordpress
image: >-
  https://upload.wikimedia.org/wikipedia/commons/thumb/a/ae/WordPress.svg/2000px-WordPress.svg.png
image-alt-text: Scrabble tiles spelling out the word website
image-link: >-
  https://upload.wikimedia.org/wikipedia/commons/thumb/a/ae/WordPress.svg/2000px-WordPress.svg.png
---
In a [previous post](/how-to-create-your-own-site-for-free) I described how one could create their own website for free, and I utilized a program called Jekyll (I will assume that you have the article, so as not to be redundant in explaining new terms). Of course, there are many options other than Jekyll, such as the popular Wordpress.org. I'm here to show you why Jekyll is the better option when deciding how to manage your site.

This is perhaps more of a CMS or no-CMS debate. A CMS is the abbreviated term for a "content management system", which is a clickable, or dynamic, WYSIWYG ("what you see is what you get") software for managing blogs and websites. It can be heavy sometimes, and is probably overkill for many personal sites.

## Of Messes and Disasters

An amazing alternative to the mess that is CMS is Jekyll, one of the more popular _static_ site generators out there. Unlike a CMS, which is dynamic and has a graphical user interface (WYSIWYG) for managing a website, static site generators are, well, static. This means that everything is done in basic text files with a "language" called Markdown. Markdown is not a hard language to learn (it is _definitely_ not as hard to learn as a traditional "programming" language, such as JavaScript), and is basically like writing a document in a text editor like Microsoft's Notepad, but instead of clicking on a button to bold or italicize a word, you would wrap 2 asterisks (\*) or underlines (\_) around it to bold or italicize the word, respectively. In Markdown, the word "Jekyll" with double asterisks wrapped around it (to bold the text), like \*\*jekyll\*\*, would appear as **Jekyll**. However, don't fret if you do not want to do this, because there are workarounds (see "Prose is Better Than Poetry").

Jekyll generates a full-blown site from just text, HTML, and CSS files, with a little bit of other good stuff, like the YAML (a recursive acronym for "YAML Ain't Markup Language") and Liquid languages. It is obviously more efficient than the clunky disaster that is Wordpress, and you can work on your blog posts entirely online or offline if you please, as well. You can do this by editing the posts in a text editor on your computer and uploading it to website hosting platform such as [GitHub Pages](https://pages.github.com/). Or, you could work online using Prose, "a content editor for GitHub." 

## Prose is Better Than Poetry

"Prose provides a beautifully simple content authoring environment for CMS-free websites. It's a web-based interface for managing content on GitHub. Use it to create, edit, and delete files, and save your changes directly to GitHub. Host your website on GitHub Pages for free, or set up your own GitHub webhook server. Prose has advanced support for Jekyll sites and markdown content. Prose detects markdown posts in Jekyll sites and provides syntax highlighting, a formatting toolbar, and draft previews in the site's full layout." -[prose.io](https://prose.io) website

If you use GitHub and GitHub Pages for your website, adding Prose to your workflow will make writing posts for your blogs easier. You could, in theory, write anywhere (on your computer or on your phone or tablet), without having to be restricted to a certain computer. It will also allow you to bold, italicize, quote, add images, add unordered (bulleted) lists, add ordered (numbered) lists, and more (rejoice, fellow human!). So you would not even need to know Markdown in order to write **blog** _posts_ "with" **_style_**. However, be aware that Prose may not work well with alternatives to GitHub Pages, such as Netlify.

For the HTML-Tricks website, we use GitHub Pages to host our site, and GitHub Pages is powered by Jekyll. We have also implemented Prose into our workflow (all it takes is a simple sign in to GitHub from the [prose.io](https://prose.io) site, and you're good to go). In fact, this post was written 100% on Prose. You can even preview your post before it's published without trouble, which is apparently a selling point for some folks.

## Closing Thoughts

