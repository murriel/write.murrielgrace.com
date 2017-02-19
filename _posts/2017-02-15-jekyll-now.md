---
layout: post
title: jekyll revisited
categories: [tech]
description: really just a shortcut placeholder with jekyll tips and tricks
---

This is a little bit of a shortcut reference guide on using Jekyll on GitHub Pages as a blogging platform.

Basic directory structure:
\_drafts
\_includes



To add a new post
To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Take a look at the source for this post to get an idea about how it works.


{% highlight ruby %}
def foo
  puts 'foo'
end
{% endhighlight %}


{% highlight yaml %}

title: yaml block

{% endhighlight %}


To add tags to posts, add the following to the Jekyll Front Matter
tags: [demo, dbyll, dbtek, sample2]

Footnotes: The shortcuts and details above were compiled from various Jekyll and theme reference guides.
