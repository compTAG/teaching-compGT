---
layout: post
title:  "Create a post!"
date:   2018-05-29
author: <a href="http://millman.us">David L. Millman</a>
categories: main
---

There are two ways to create a post. The easiest is email the content of your
post and I will format it and post it for you.  Or you can create a post by
submitting a pull request on github.  Below are some of the Jekyll specifics.

Creating posts is very easy with Jekyll.  There are many tutorials, but, at
their core, a post is a markdown file in the `_posts` directory.

First, create a markdown file in posts with the format
`_posts/YYYY-MM-DD-short-descriptive-name.md`

Add a header to the file in the format

    ---
    layout: post
    title:  "Create a post!"
    title:  TODO_ADD_TITLE
    date:   TODO_ADD_DATE
    author: TODO_ADD_NAME
    categories: main
    ---

Update the title to be the title, date, and author for your entry.  The year
should be formatted as `YYYY-MM-DD`.  You do not need to make any changes to the
layout or the categories. For example, the header for this post could be:

    ---
    layout: post
    title:  "Create a post!"
    date:   2018-05-29
    author: David L. Millman
    categories: main
    ---

Next fill in your content in markdown.  Markdown is a simple text format created
by John Gruber.  It is like latex but much simpler.  For more on markdown see
the [darning fireball website][markdown].

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of
Jekyll.

[markdown]:  https://daringfireball.net/projects/markdown/
[jekyll-gh]: https://github.com/mojombo/jekyll
[jekyll]:    http://jekyllrb.com
