---
layout: post
title:  "Let's Swift!"
date:   2015-11-27 16:00:00 +0100
categories: jekyll test
---
Let's see if this works

{% highlight swift %}
protocol Test {
	func test()
}
struct Tested : Test {
	func test() {
		print("Sucess")
	}
}
{% endhighlight %}

Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/