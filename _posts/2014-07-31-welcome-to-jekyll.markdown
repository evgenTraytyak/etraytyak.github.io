---
layout: post
title:  "Welcome to Jekyll!"
date:   2014-07-31 23:38:01
categories: jekyll update
published: true
excerpt: 'You will find this post in your'
---
You'll find this post in your `_posts` directory - edit this post and re-build (or run with the `-w` switch) to see your changes!
To add new posts, simply add a file in the `_posts` directory that follows the convention: YYYY-MM-DD-name-of-post.ext.

Jekyll also offers powerful support for code snippets:

### Ruby
{% highlight ruby linenos %}
def show
  puts "Outputting a very looooooong line"
  @widget = Widget(params[:id])
  respond_to do |format|
    format.html # show.html.erb
    format.json { render json: @widget }
  end
end
{% endhighlight %}

### Javascript
{% highlight javascript linenos %}
function multipleContexts( selector, contexts, results ) {
  var i = 0,
    len = contexts.length;
  for ( ; i < len; i++ ) {
    Sizzle( selector, contexts[i], results );
  }
  return results;
}
{% endhighlight %}

### CSS
{% highlight css linenos %}
html, body { height: 100%; }

body {
  font-family: 'Helvetica Neue', Arial, sans-serif;
  font-size: 16px;
  line-height: 1.5;
  font-weight: 300;
  background-color: #fff;
}

h1, h2, h3, h4, h5, h6 { font-size: 100%; font-weight: 400; }

a         { color: #2a7ae2; text-decoration: none; }
a:hover   { color: #000; text-decoration: underline; }
a:visited { color: #205caa; }

{% endhighlight %}

Check out the [Jekyll docs][jekyll] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll's GitHub repo][jekyll-gh].

[jekyll-gh]: https://github.com/jekyll/jekyll
[jekyll]:    http://jekyllrb.com
