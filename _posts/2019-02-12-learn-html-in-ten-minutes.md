---
published: true
layout: right-sidebar
description: Make today the day you finally learn to build a website
permalink: /learn-html-in-ten-minutes
image: >-
  https://www.maxpixel.net/static/photo/1x/Code-Data-Programming-Code-Computer-Programming-944504.jpg
image-alt-text: Code in a text editor
image-link: >-
  https://www.maxpixel.net/static/photo/1x/Code-Data-Programming-Code-Computer-Programming-944504.jpg
---
## Hello Hello
In the next ten minutes, I'll teach you everything that you need to know about HTML, and if you'd like to continue, I also included how to get started building your very own website. Start your timer. On your mark, get set, go!

## 1. Hello HTML
So what is HTML anyway, and why is it so important? HTML, which stands for "HyperText Markup Language", is a fundamental part of every website. If you see words on any website, chances are that those words were written in an HTML file. To write your first line of code (which many call a "Hello World" application, for obvious reasons), fire up any text editor (Microsoft Notepad, Apple TextEdit - as long as it is not something like Microsoft Word, which is a _rich_ text editor, not a regular text editor) and type in the following:

\<!DOCTYPE html>

\<html>
  
\<body>
  
\<h1>Hello World!\</p>

\<p>Hello again.\</p>
  
\<body>
  
\</html>

Now go ahead and save the file with a file extension of ".html" or ".htm" (either is fine). Now open the file in your browser (double-clicking usually works), and voila! You should see the text "Hello World" on your screen (if you didn't, make sure that you did not omit an angle bracket "<"). 

Okay, so the first line (\<!DOCTYPE html>) is telling the browser that it's looking at an HTML file. Notice how the next lines of code seem to be doubled? That's because each of those words in angle brackets are called "tags", which tells the browser how to display the text. The opening tag "\<html>", for example, always has a closing tag (\</html>), which is denoted by a forward slash, while a line break tag does not have a closing tag, and is merely "\<br>". The next tag, "\<body>", tells the browser that anything in between the opening body tag ("\<body>") and closing body tag ("\</body>") should be displayed. The "h1" (header 1, out of 6 - header 1 is usually the biggest font size) and the "p" (paragraph) tag, of course, is displaying the text "Hello World!" and "Hello again.", respectively. Pat yourself on the back, you've just done something amazing, and the only way to go from here is up (well, actually, it's down, because you'll need to scroll down to view the rest of this article)!

## 2. Hello CSS
Now go back to your HTML file, and at the top, between the opening "html" and "body" tags, add an opening and closing "head" tag. Your file should now look like this:

\<!DOCTYPE html>

\<html>

**\<head>**

**\</head>**
  
\<body>
    
\<h1>Hello World!\</p>

\<p>Hello again.\</p>
  
\<body>
  
\</html>

The "head" tag is mainly used for what is known as "metadata", and contains links and such to external CSS files (beyond the scope of this article), but most notably the "title" of the page. Bear in mind that this is actually the title for the browser tab, so it will not show up on the web "page" itself. Now, within the "head" tags, why don't you add an opening and closing "title" tag, and put whatever text you'd like. Your HTML file should look somewhat like this:

\<!DOCTYPE html>

\<html>

\<head>

**\<title>**Whatever You'd Like**\</title>**

\</head>
  
\<body>
   
\<h1>Hello World!\</p>

\<p>Hello again.\</p>
  
\<body>
  
\</html>

Again, save the file and reload the page in your browser to see changes. If you've seen the browser tab at the top say what you wrote in your "title" tags, then good for you. 

The "head" tag is sometimes also used for adding CSS to a webpage. CSS stands for "Cascading Style Sheets", and if HTML is thought of like the skeleton of a webpage, then CSS would be the skin and makeup (there is also a language called JavaScript that is beyond the scope of this article, but in this analogy, JavaScript would be the muscles of a webpage). Let's make the text in your "p" tags the color red. Follow below:

\<!DOCTYPE html>

\<html>

\<head>

\<title>Whatever You'd Like\</title>

**\<style>**

p {color: red;}

**\</style>**

\</head>
  
\<body>
    
\<h1>Hello World!\</p>

\<p>Hello again.\</p>
  
\<body>
  
\</html>

Within the "style" tags (which is within the "head" and then the "html" tags), the "p" is selecting the "p" tag, then whatever comes next in the brackets ("\{" and "\}") will style whatever is in the "p" tag, and in this case the color is changed to red. Notice the header "Hello World!" is still not the color red.

If I had wanted to make the entire body, and not just the "p", red, then I could have written "body" instead of "p" in the "style" tag, which is totally possible. But let's say I want the "body" to be blue instead of red... 

\<!DOCTYPE html>

\<html>

\<head>

\<title>Whatever You'd Like\</title>

\<style>

p {color: red;}

**body {color: blue;}**

\</style>

\</head>
  
\<body>
    
\<h1>Hello World!\</p>

\<p>Hello again.\</p>
  
\<body>
  
\</html>

Okay, now everything (even the header) is blue. Now go ahead and try this:

\<!DOCTYPE html>

\<html>

\<head>

\<title>Whatever You'd Like\</title>

\<style>

**body {color: blue;}**
p {color: red;}

\</style>

\</head>
  
\<body>
    
\<h1>Hello World!\</p>

\<p>Hello again.\</p>
  
\<body>
  
\</html>

Huh. Now the "p" is red, but the header is blue. How can this be, you ask? Because a browser reads CSS in order, and whatever is more specific is what the browser shows. In this example, the "p" tag is more specifically inside the "body" tag, so it becomes red. In the previous example, I had set "p" to be red and then changed the color of the body to blue, so CSS made everything blue because the computer/browser reads code in order. And that's the beauty of coding! 

## 3. Hello Git

What if we had wanted to go back in time to see the HTML file before we started changing colors. Well, that's what [Git](https://git-scm.com/) is for! Git is a version control system for (source) code, which is fancy terms for "Google Drive for code" (or Dropbox or OneDrive, everybody is entitled to their own opinions). Git is used in the computer terminal and is a bit over the scope of this article, but it is important that you note the importance of this very important little tool.  

## 4. Hello GitHub Pages (and Jekyll)
No matter if you use Git or not, [GitHub](https://github.com/) (or one of it's alternatives, such as [GitLab](https://about.gitlab.com/), Atlassian [BitBucket](https://bitbucket.org/), or [Sourceforge](https://sourceforge.net/)) is a must-have. It makes Git "remote", which is another fancy term for syncing "repositories" (aka project folders) of code online. As of the time of this writing, GitHub now offers free private and public repositories. GitHub has a pretty nifty feature called [GitHub Pages](https://pages.github.com/) that can generate a website from your repository on GitHub for free. It utilizes something called [Jekyll](https://jekyllrb.com/), which takes plain text and turns it into static websites (so the total opposite of [Wordpress](https://wordpress.com/), [Wix](https://www.wix.com/), or [Squarespace](https://www.squarespace.com/), which are all WYSIWYG - "what you see is what you get" - and dynamic). But it's really simple and easy, and with just a few steps you can have a site up and running. On a computer that you own (or one that you have permission to install software on), navigate to the [Jekyll Docs](https://jekyllrb.com/docs/installation/) and install Jekyll (I _strongly_ recommend that you follow one of the [Guides](https://jekyllrb.com/docs/installation/#guides) on the page). 

Now that you have successfully completed the installation of Jekyll, go back to the [home page](https://jekyllrb.com/) and follow the "Quick-start Instructions". Do you see anything! Yeah, that's your amazing new website! Congrats! The design you are seeing is called Minima, and it is totally free (you can view the source code on GitHub [here](https://github.com/jekyll/minima)). You can edit this theme if you'd like, but for now, let's work on getting it connected to GitHub Pages. Obviously, you'll need a GitHub account. Once you are logged in to GitHub, create a new repository by either clicking on one of the green (at the time of this writing) buttons that say "New" or the plus "+" sign at the top, then "New repository" in the dropdown menu. 

Once you are in the "New repository" page, if you've followed the instructions so far, your local (not-on-GitHub-yet) site (folder) should be called "my-awesome-site". If not, that's okay. In the GitHub "New repository" page, put the name of the Jekyll site that you generated (in the example it would be "my-awesome-site". Then, at the bottom, click on "Add .gitignore" and search for and click on "Jekyll" in the dropdown menu (a gitignore is basically telling GitHub that we do not need to sync certain files every time you "save" the repository, and GitHub now knows automatically which files are Jekyll files that need to be ignored and which files are _your_ files, which is awesome in itself). Then, click "Initialize this repository with a README". Finally, click "Create repository". Yay, you've just created your first repository on GitHub! 

Now, you'll want to open your local folder with Jekyll called "my-awesome-site" or whatever you chose to name it, and then drag and drop all of the contents of the folder into the GitHub repository (pretty self-explanatory). Once everything loads, scroll down the GitHub page and click on "Commit" (basically like a "file save", but you write a comment everything time). Once you've verified that the files uploaded to GitHub, go ahead and delete the folder on your computer (in this tutorial, we will _not_ be utilizing Jekyll in the terminal and live previews).  

You won't see your site online just yet, as we still have two more things to do. First of all, you'll need to:

1. Navigate back to the "Code" tab, if you are not there already
2. Click on "Branch: master" and type in "gh-pages" (case-sensitive) and hit enter on your keyboard
3. Go to the "Settings" tab and click on "Branches", then under "Default branch", change it from "master" to "gh-pages"
4. Navigate back to the "Code" tab, and click on where it says "2 branches" (should be next to "X commits" and "0 releases")
5. Click the trash icon on any row marked "master"

Explanation: GitHub Pages works with GitHub Users, GitHub Projects, and GitHub Organizations. If you were to create a user page, you would have had to name your repository after your username, such as "username.github.io" instead of "my-awesome-site". A GitHub Projects page is what we are working on right now, and the steps that were outlined above dictate how to change the branch from the default ("master") to the GitHub Pages branch ("gh-pages"), which will help us avoid any trouble in the near future. And GitHub Organizations pages are conceptually like GitHub User pages, in that they are named after the organization name ("org-name.github.io"). A GitHub User can create many organizations but should use them wisely. 

But wait, the site doesn't even look good anymore. That is because we need to modify a setting in your "\_config.yml" file. The "\_config.yml" file is like the settings hub for your entire Jekyll site and is used to manage things such as your name, email address, the "title" (remember earlier) of your site, and a description of your site. But it also has options for a "baseurl", and that is what we are going to change. Right now, the "baseurl" should be blank, but we will need to change it to "/repository-name". So if the repository name was "my-awesome-site", under the "baseurl" in the "\_config.yml", I would put "/my-awesome-site". It is important that you do _not_ include a forward slash at the end (beyond the scope of this article). Follow the steps below in order to modify your "\_config.yml" file:

1. Navigate back to the "Code" tab, if you are not there already
2. Find the file called "\_config.yml" and click on it to open it
3. Find the pencil icon near the top right of the file (it will be next to "Raw", "Blame", and "History") and click it
4. Now scroll to baseurl and make the change that was described in the above paragraph

Congratulations! Your site should be up and running at "your-github-username.github.io/your-repository-name"! Why don't you change a few more items in the "\_config.yml" file, such as your email address, if you haven't already. You have really accomplished a lot. 

## 5. Hello Prose
Remember how I told you to delete your local folder of code because now you are working online. I just want to let you know that you don't need to do that all of the time, and since this is a beginner's tutorial I did not want to put too many unnecessary details. In fact, GitHub and Git are popular because of something called "Git init/clone/pull/push", and if you are interested you can read about it here on the [Git](https://git-scm.com/) official site, specifically the [Pro Git Book](https://git-scm.com/book/en/v2). 

Usually, you could work locally on your [Jekyll posts](https://jekyllrb.com/docs/posts/) and then "push", or upload, your changes to GitHub to see it reflected online. But, let's say that you were on the go and wanted to write a post, but didn't have access to your production computer/laptop. But you had your tablet or cellular phone. Then, you could write your posts online with a free tool called [Prose](https://prose.io/). Prose is pretty much an online text editor dedicated to Jekyll, GitHub Pages, and blogs. It works best with a GitHub Pages site and requires a GitHub account (which we have now since we've been following along with the article, right?). 

Anyway, once you head over to [prose.io](https://prose.io/) and authorize (sign in) to GitHub, you'll see your repository (project folder) pop up. You can click "View Site" if you'd like, but once you're ready head back to [prose.io](https://prose.io/) and click "View Project" instead. If you have a folder called "\_posts" click on that, then click on "New File". If you do not have a "\_posts" folder, then just click "New File". Now click the top text to change the file name (it must have the same naming convention of "YYYY-MM-DD-article-name.md"). If you do not have a "\_posts" folder, then once you click "New File", prepend "\_posts" to the name, so now for everyone it should say: "\_posts/YYYY-MM-DD-article-name.md". 

Now, feel free to edit and save by using the provided controls or clicking `ctrl+s`, which is significantly faster. You can preview the Markdown by clicking the eye icon, change metadata (if you're wondering what this is, I _really_ _strongly_ suggest reading the official Jekyll step-by-step guide all the way through - it's really short, and it's right [here](https://jekyllrb.com/docs/step-by-step/01-setup/)), change settings, and save the file (albeit the long way).

And when you're finished editing a post, click "Unpublished" at the top to mark the page for publishing, then once you save the page again, it should say "Published". Be sure to wait a couple minutes because the changes are not usually instantaneous (that is what the Jekyll live preview is for, but that was beyond the scope of this article). 

## Goodbye
And there you have it, folks. Your very own free website with a way to add more content. I hope that this post was helpful for you. Have a nice day!
