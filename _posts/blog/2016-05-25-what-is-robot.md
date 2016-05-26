---
layout: post
title: "What is robotics?"
modified:
categories: blog
excerpt:
tags: []
image:
  feature: whatisrobot.jpg
  credit: International Institute for Research
  creditlink: http://www.impactfactorjournals.com/
date: 2016-05-25T15:39:55-04:00
---

The definition explains robotics as a branch of engineering that involves the conception, design, manufacture and operation of robots. This field overlaps with electronics, computer science, artificial intelligence, mechatronics, nanotechnology and bioengineering.

Isaac Asimov is known as the science-fiction author and also the first to use the term robotics in a short story in the 1940s. He suggested three principles to guide the behavior of robots and smart machines, the _Three Laws of Robotics_:

*Robots must never harm human beings
*Robots must follow instructions from humans without violating rule 1
*Robots must protect themselves without violating the other rules

Nowadays, robots work in many different ways. They are machines that can be used to do jobs, sometimes by themselves and sometimes with a person telling them what to do. NASA for example, uses robots to many functions:

*Robotic arms on spacecraft can move large objects in space
*Robotic spacecraft can visit other worlds
*Robotic airplanes can fly without a pilot aboard

NASA and other companies are also studying new types of robots that will work with people and help them. TED is a nonprofit devoted to spreading ideas with powerful talks that have already talked about our future depending on robots, in a way that robots can help us instead of replacing us. Below, there is a video where the roboticist Rodney Brooks introduces Baxter, the robot which could work alongside population.


<iframe width="560" height="315" src="http://www.youtube.com/watch?v=nA-J0510Pxs" frameborder="0"> </iframe>

<iframe width="560" height="315" src="//www.youtube.com/embed/pdSp4Y4GOQs" frameborder="0"> </iframe>

<iframe width="560" height="315" http:"//www.youtube.com/embed/watch?v=nA-J0510Pxs" frameborder="0"> </iframe>

Video embeds are responsive and scale with the width of the main content block with the help of [FitVids](http://fitvidsjs.com/).

Not sure if this only effects Kramdown or if it's an issue with Markdown in general. But adding YouTube video embeds causes errors when building your Jekyll site. To fix add a space between the `<iframe>` tags and remove `allowfullscreen`. Example below:

{% highlight html %}
<iframe width="560" height="315" src="http://www.youtube.com/embed/PWf4WUoMXwg" frameborder="0"> </iframe>
{% endhighlight %}

And here's a Vimeo embed for testing purposes.

<iframe src="//player.vimeo.com/video/98146708?title=0&amp;byline=0" width="500" height="281" frameborder="0"> </iframe>

<iframe src="https://youtu.be/nA-J0510Pxs" width="500" height="281" frameborder="0"> </iframe>





**References:**


[jekyll-gh]: https://github.com/jekyll/jekyll
[jekyll]:    http://jekyllrb.com
