---
layout: post
title:  "Hello New Blog!"
date:   2017-04-26 08:01:36 -0700
categories: jekyll update
googlewebfonts: Raleway
---
<script type="text/x-mathjax-config"> 
    MathJax.Hub.Config({ 
        "HTML-CSS": { scale: 100, linebreaks: { automatic: true } }, 
        SVG: { linebreaks: { automatic:true } }, 
        displayAlign: "center" });
</script>

<script type="text/javascript" async
  src="https://cdn.mathjax.org/mathjax/latest/MathJax.js?config=TeX-AMS-MML_HTMLorMML">

</script>



Moving to a new place can be hectic and tiresome. I am moving my blog, from [here](http://quipu-strands.blogspot.com/), and it’s none of those.[^1]

Yeesh, a feeble attempt at a [Paraprosdokian](https://en.wikipedia.org/wiki/Paraprosdokian). Anyhoo.

I tend towards writing technical posts when I tend towards writing at all these days, and [blogger](https://www.blogger.com) doesn’t give me the presentation options I need. So, for now, its GitHub pages[^2], but with my own domain. That way, if I decide to move again, my (almost non-existent) readers won’t be sent scrambling to find my (almost non-existent) content.

The old blog was titled “Random Thoughts”. I wanted something different and bit more original this time, so I Googled “Not So Random Thoughts”. Obviously. 

So many hits it isn't even funny. So many, that you couldn't squint and ignore. And that is exactly why you are stuck with "A Not So Primordial Soup"; which, by the way, does a good job of telling you that this is going to be a mixed bag of the deep and the frivolous.

Just for the record, "The Psionic Poodle" was on the list. Since that isn't the title, joy to us, things might have been worse. 

Now for some quick tests to see if this platform holds up. Grouping them here, so that if I switch to a new platform/theme etc, I can use this post as a quick check to see if the various non-text entities I use are displayed correctly. My regression tests, if you will. 

* Math. Trust me this is going to come up.
    
    $$
    \begin{align}
    &\text{Cauchy-Schwarz: }||x+y||^2  \leq (||x||+||y||)^2 \\
    &\text{Holder: }\sum_{n=1}^{\infty}\frac{(a_1 + a_2 + ... + a_n)^p}{n}  < \Bigg(\frac{p}{p-1}\Bigg)^p \sum_{n=1}^{\infty} a_n^p 
    \end{align}
    $$
    
* Images. Of course. 
  {% include image.html
            img="/blog/assets/yosemite-random.jpg"
            title="Yosemite"
            caption="From a trip to Yosemite. Wow, captioning in Kramdown <a href='https://superdevresources.com/image-caption-jekyll/'>isn't straightforward!</a>" %}
  
* Code. You bet. 
    {% highlight Python %}
  def dot_product(v1, v2):
    # v1, v2 are lists
    result = None
    if len(v1) == len(v2):
        result = sum(map(lambda x: x[0] * x[1], zip(v1, v2)))
    return result
  {% endhighlight %}
* Tables. Basic. _Just-in-case-I-need-them-but-I-really-don't-think-I-need-them._

  |-----------------+------------+-----------------+----------------|
  | Default aligned |Left aligned| Center aligned  | Right aligned  |
  |-----------------|:-----------|:---------------:|---------------:|
  | First cell      |Second cell | **Third cell**  | fourth cell    |
  |-----------------+------------+-----------------+----------------|
  {:.mbtablestyle}
  

During my research to move, I discovered, quite to my surprise, that having a reliable comment system is something of a challenge. _In 2017_. I mean in a few years I could be sitting in my self-driving car (Update in 2022: yeah, this dated well.) and worrying about comment systems.

More updates from 2022: When I had initially moved to GitHub pages, commenting systems left much to be desired. I did have [Talkyard](https://www.talkyard.io/) on here for a while, which is a nifty system. But now we have options like [utterances](https://utteranc.es/) and [giscus](https://giscus.app/), which feel like a more natural fit for something that's hosted on GitHub. I am going to integrate one of them soon.

See you later then?
<br>
 
 
 _  _  _  _
<br>

[^1]: If that link doesn’t work, it means I have managed to miraculously overcome my laziness and migrated all my posts. But don’t worry, that’s not bound to happen anytime soon.
[^2]: As of writing this post. Check the "About" section for details and updates.
