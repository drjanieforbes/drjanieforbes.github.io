---
layout: post
title:  "Welcome to my research blog!"
date:   2017-02-24 14:30:05 -0500
categories: jekyll update
---
What I hope to accomplish with this blog is to feature open-access research projects that I am currently working on.

This site is built with Jekyll, which offers powerful support for code snippets:

Ruby:
{% highlight ruby %}
def print_hi(name)
  puts "Hi, #{name}"
end
print_hi('Tom')
#=> prints 'Hi, Tom' to STDOUT.
{% endhighlight %}

R:
{% highlight r %}
# using google, this will return lat/lon for Baltimore, Maryland
CenterOfMap <- geocode("Baltimore, MD")
# get the google map of Baltimore
Baltimore <- get_map(c(lon=CenterOfMap$lon, lat=CenterOfMap$lat),zoom = 12,
    maptype = "terrain",
    source = "google")
my.base.map <- ggmap(Baltimore)
{% endhighlight %}

Python:
{% highlight python %}
try:
    z = int(x) + int(y)     # if successful, z will contain the sum
except ValueError:
    # nope, there's a problem
    print('x or y or both contain at least one non-digit character')
    z = -1

print('%s + %s is: %s' %(str(x),str(y),str(z)))
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

#To add new posts, simply add a file in the `_posts` directory that follows the #convention `YYYY-MM-DD-name-of-post.ext` and includes the necessary front matter. #Take a look at the source for this post to get an idea about how it works.

Visit [my github][mygithub]

[jekyll-docs]: https://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/
[mygithub]: https://github.com/drjanieforbes
