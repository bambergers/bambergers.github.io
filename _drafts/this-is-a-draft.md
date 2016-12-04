---
layout: base
title:  "[DRAFT] This is a draft"
categories: jekyll github tools
---

Drafts don't have a date yet and reside in the `_drafts` folder.

To preview the site with drafts, simply run `jekyll serve` with the `--drafts` switch.

### Workflow
You can create and edit posts locally, running `jekyll serve --watch`, which launches a web server on [local port 4000](http://0.0.0.0:4000/) and auto-regenerates the site when a file is updated. To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.md` and includes the necessary front matter. Once you commit and push the changes to GitHub, they're getting rendered and published at [bambergers.github.io](https://bambergers.github.io/).

We probably won't include many code snippets on a family blog, but in case we want to, this is how to do it:

{% highlight ruby %}
def greet(name)
  puts "Hi, #{name}"
end
greet('Bambergers')
#=> prints 'Hi, Bambergers' to STDOUT.
{% endhighlight %}
