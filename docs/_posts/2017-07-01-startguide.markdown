---
layout: post
title:  "Webcomic Jekyll Theme!"
date:   2017-07-13 14:10:24 -0700
categories: start
---

# PREREQUISITES

You will need to install some things in order to use the site.

## A Github Account

Once your site is completed, you'll be hosting it on Github Pages, a free service offered to anyone with a Github account.

[Sign up for Github here](https://github.com/join)

**Note:** You can use a different webhost if you want. But Github Pages works well with Jekyll because you can push your Jekyll source files directly to

## A Text Editor

Most computers come pre-installed with a
This isn’t required, but it’s way easier and more fun to work on markdown files with a text editor. Try [Sublime](https://www.sublimetext.com/) or [Atom](https://atom.io/) (both free).

I use [Atom](https://atom.io/) with the [fairyfloss](https://atom.io/themes/fairyfloss) theme for maximum kawaii.

![](/images/atom.png)

## Open Terminal

If you’re on a Mac, go to your search bar and open Terminal. It will look something like this.

![](/images/terminal.png)
Once you install Jekyll, you'll tell it what to do by typing commands here. I'll tell you exactly what to type, but I do recommend taking some time to learn these really easy commands.

## Install Jekyll

The easiest way to install Jekyll is to using RubyGems.
[Ruby Installation Guide.](https://rubygems.org/pages/download)

Once you have Ruby installed, you can simply open up your Terminal and type

```
gem install jekyll
```

[Jekyll Installation Guide](https://jekyllrb.com/docs/installation/)

Now that you have Jekyll installed, let’s try using it to generate a site. Go to Terminal and navigate to a folder where you want your website to be. Then, type the following and hit enter:

```
jekyll new my-comic
```
This will create a new folder called "my-comic" and fill it with the folders and files Jekyll needs to build a static site.

Next, you'll need to navigate into that new folder.

```
cd my-comic
```
to move inside that directory, then type

```
jekyll serve
```

This will build your website and host it temporarily on your local server. Paste `http://127.0.0.1:4000` into a browser to see it!

# STEP TWO: Download the Webcomic Code

1. Go here and download the code. You can save it to wherever you want; just make sure you remember where it is.
2. Use Terminal to navigate to where you’ve saved the directory. Type `jekyll serve` into Terminal.

3. If everything’s in the right place, Jekyll will serve the webcomic site to your local server! Paste `http://127.0.0.1:4000` into a browser to see it!

# STEP FOUR: Add your content!

[Read about using the code here](/docs/howto.html).

## Pushing to Github Pages

Github has a fantastic guide for creating a Github Page and pushing your code to live.
[Github Pages Guide](https://pages.github.com/)
I won't waste your time trying to duplicate it. When you're finished building your site, go ahead and try it!
