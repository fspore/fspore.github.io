---
layout: post
title:  "MarkDown Test!"
date:   2019-12-19 18:20:41 +0800
categories: jekyll update
---



{% highlight java %}
    private void qsort(int[] arr, int lo, int hi)
    {
        if(lo >= hi) return;
        int p = partition(arr, lo, hi);
        qsort(arr, lo, p-1);
        qsort(arr, p+1, hi);
    }
// this is a comment in code snippet.
{% endhighlight %}



Check out the [Jekyll docs][jekyll-docs] for more info on how to get the most out of Jekyll. File all bugs/feature requests at [Jekyll’s GitHub repo][jekyll-gh]. If you have questions, you can ask them on [Jekyll Talk][jekyll-talk].

[jekyll-docs]: http://jekyllrb.com/docs/home
[jekyll-gh]:   https://github.com/jekyll/jekyll
[jekyll-talk]: https://talk.jekyllrb.com/

