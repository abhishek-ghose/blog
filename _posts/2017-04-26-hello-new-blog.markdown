---
layout: post
title:  "Hello New Blog!"
date:   2017-04-26 08:01:36 -0700
categories: jekyll update
googlewebfonts: Raleway
---
<script type="text/x-mathjax-config"> 
    MathJax.Hub.Config({ 
        "HTML-CSS": { scale: 90, linebreaks: { automatic: true } }, 
        SVG: { linebreaks: { automatic:true } }, 
        displayAlign: "center" });
</script>

<script type="text/javascript" async
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">

</script>



Moving to a new place can often be exciting, hectic and even tiresome, all at the same time. I am moving my blog, from [here](http://quipu-strands.blogspot.com/), and it’s none of those.[^1]

I tend towards writing technical posts when I tend towards writing at all these days, and [blogger](https://www.blogger.com) doesn’t give me the presentation options I need. So, for now, its GitHub pages[^2], but with my own domain. That way, if I decide to move again, my (almost non-existent) readers won’t be sent scrambling to find my (almost non-existent) content.

The old blog was titled “Random Thoughts”. I wanted something different and little more original this time, so I Googled “Not So Random Thoughts”. Obviously. 

Yeah, right. 

So many hits it isn't even funny. So many, that you couldn't squint and ignore. And that is exactly why you are stuck with "A Not So Primordial Soup"; which, by the way, does a good job of telling you that this is going to be a mixed bag of the deep and the frivolous.

Just for the record, "The Psionic Poodle" was on the list. In case you were wondering if I can be fun. 

Now for some quick tests to see if this platform holds up. Grouping them here, so that if I switch to a new platform/theme etc, I can use this post as a quick check to see if the various non-text entities I use are displayed correctly. 

* Math. Trust me this is going to come up.
    
    $$
    \begin{align}
    &\text{Cauchy-Schwarz: }||x+y||^2  \leq (||x||+||y||)^2 \\
    &\text{Holder: }\sum_{n=1}^{\infty}\frac{(a_1 + a_2 + ... + a_n)^p}{n}  < \Bigg(\frac{p}{p-1}\Bigg)^p \sum_{n=1}^{\infty} a_n^p 
    \end{align}
    $$
    
* Images. Of course. 
  {% include image.html
            img="assets/yosemite-random.jpg"
            title="Yosemite"
            caption="Trip to Yosemite. Wow, captioning in Kramdown <a href='https://superdevresources.com/image-caption-jekyll/'>isn't easy!</a>" %}
  
* Code. We are going to need code.
    {% highlight Python %}
  def dot_product(v1, v2):
    # v1, v2 are lists
    result = None
    if len(v1) == len(v2):
        result = sum(map(lambda x: x[0] * x[1], zip(v1, v2)))
    return result
  {% endhighlight %}
* Tables. Basic. I mightn't need them, but since we're on a roll here ...

  |-----------------+------------+-----------------+----------------|
  | Default aligned |Left aligned| Center aligned  | Right aligned  |
  |-----------------|:-----------|:---------------:|---------------:|
  | First cell      |Second cell | **Third cell**  | fourth cell    |
  |-----------------+------------+-----------------+----------------|
  {:.mbtablestyle}
  

During my research to move, I discovered, quite to my surprise, that having a reliable comment system is something of a challenge. _In 2017_. I mean in a few years I could be sitting in my self-driving car and worrying about comment systems.

Either platforms have their own systems tied to them (like blogger) or there are third party plug-n-play systems like [Disqus](https://disqus.com/) and [Discourse](https://www.discourse.org/). Maybe I shouldn’t bundle them together since Disqus receives a lot of hate (albeit easy to set up), while Discourse receives more of critique for their idiosyncratic system, if that: many people seem to like it. Personally, I almost like it. 

There are several self-hosted solutions in this category too, and I am going to try one of those: [Isso](https://posativ.org/isso/). Will take a while to get it running I suppose. I’ve had this small-ish Linode server running forever, for which I convince myself to pay as an emergency back-up machine. You know, for times when I'd need to save the world by running a few experiments, and I really don't want to delay imminent glory by doing stupid things like looking for machines to run them on. You would be surprised to know that need has never come up. So it better get to hosting some comments if it wants me to keep paying for it. 

See you later then?
<br>
 
 
 _  _  _  _
<br>

[^1]: If that link doesn’t work, it means I have managed to miraculously migrate all my posts. Overcoming my lethargy would be the miracle here. But don’t worry, that’s not bound to happen anytime soon.
[^2]: As of writing this post. Check the "About" section for details and updates.
