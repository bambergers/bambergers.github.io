---
layout: base
title:  "Jekyll <3 GitHub Pages"
date:   2014-12-09 16:53:04
categories: jekyll github tools
---

This blog / lab notebook runs on [Jekyll][jekyll], which in turn runs on [GitHub Pages](https://pages.github.com). A powerful combination of tools, yet quite easy to use.

[jekyll]: http://jekyllrb.com

I didn't even have to install Jekyll, as it's already built into GitHub Pages. It comes with a `_posts` directory, that holds all my [Markdown](https://help.github.com/articles/markdown-basics/) files.

First, I create and edit my posts locally, running `jekyll serve --watch`, which launches a web server on my [local port 4000](http://0.0.0.0:4000/) and auto-regenerates my site when a file is updated. To add new posts, I simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. Once I commit and push the changes to GitHub, they're getting rendered and published on [b4mboo.github.io](https://b4mboo.github.io/). You're looking at it.

Jekyll also offers powerful support for code snippets:

{% highlight ruby %}
def greet(name)
  puts "Hi, #{name}"
end
greet('b4mboo')
#=> prints 'Hi, b4mboo' to STDOUT.
{% endhighlight %}

The best part, however, is the ability to search my blog by using GitHub's code search. A blog which I can't search is useless to me. A lot of the commercial alternatives no longer offer full text search. So I guess, I'd rather stick with the free service GitHub offers. ;-)

Last, but not least, it's only fair to mention that I'm using the [Dinky theme](https://github.com/broccolini/dinky) for my blog. Again, you're looking at it. Personally, I like it very much as it's simple, but beautiful. Thanks, [@broccolini](https://github.com/broccolini), for creating it and open sourcing it.
