---
layout: page
title:  "[DRAFT] How to work with this blog"
---

You can use this draft as a template for new posts. Simply duplicate and rename it.

### Workflow
Drafts don't have a date yet and reside in the `_drafts` folder. You can create and edit posts locally, running `jekyll serve --watch --drafts`, which launches a web server on [local port 4000](http://0.0.0.0:4000/) and auto-regenerates the site when a file is updated. To add new posts, simply add a file in the `_posts` directory that follows the convention `YYYY-MM-DD-name-of-post.md` and includes the necessary front matter. Once you commit and push the changes to GitHub, they're getting rendered and published at [bambergers.github.io](https://bambergers.github.io/).

### Diary Entries
Most of this blog's entries in English, while our diary will be in German. From a technical point of view, we just wrap them in code blocks. This is how to do it:

{% highlight markdown %}
# Sonntag, 4. Dezember
Bald geht es los. Der Blog ist schon fast fertig.
Tagebucheinträge wie dieser werden immer in Deutsch erscheinen. Der Rest des Blogs bleibt Englisch.

Viel Spaß beim Lesen!
{% endhighlight %}

### Pictures
Let's post photos, but at the same time, try to not expose too much private information to the public. Hence, no faces, no private information.
Photos will be posted in their native resolution, i.e. as created by our mobile phones. Just copy them to `/photos` and give them a descriptive name.
The pictures will be geo-tagged by our phones. As long as we're aware of that, it shouldn't be a problem to leave it that way.

As an example, here's a picture of the golden pavilion in Kyoto:

![]({{ site.url }}/photos/golden pavilion.jpg)
