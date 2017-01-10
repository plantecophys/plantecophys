---
layout: post
title: Site launched
date: 2017-01-06
---

<p>So, I guess I <i>finally</i> got around to launching this website. It was a long time coming, and with me coming from no real coding background, it was a rocky road. I used to have homepages when I was a kid (some 15 years ago), but back then you didn't have to think about mobile device readability and such. All the same, I saw it as a nice little challenge for myself then and now again.

I had some thoughts about my to-be pages before I decided on the way to approach building them:</p>

* Free of cost while no ads (sounds impossible already...)
* Simplicity in design and code
* Need to work also on mobile devices
* Possibility for learning something while making them

<p>Eventually I decided to host static pages on <a href="https://github.com/AnttiTenkanen/anttitenkanen.github.io">GitHub</a>, which also provides a <a href="https://jekyllrb.com/">Jekyll</a>-powered solution for blogging. The mobile-first design is basically coming from <a href="https://getbootstrap.com/">Bootstrap</a> style sheets. Because of a very different previous experience I had with page building, there was a lot of re-thinking to do, especially with the way Jekyll templating and directory structure works.</p>

<p>But the biggest difficulty I actually had was how to itegrate some kind of possibility for commenting into the static design. It would have been simple to externalize some JavaScript commenting database like Disqus, but it would have meant giving away my commenters' data to the service provider. I then looked into my options and found solutions like <a href ="https://posativ.org/isso/">isso</a>, which is self-hosted and enables anonymous commenting. However, it seemed a little bit too much work for me to implement and maintain. Eventually I also found <a href="https://commentit.io/">Comm(ent|it)</a>, a fresh-off-the-oven solution meant exclusively for use with GitHub Pages (comments are processed as pull-requests straight into the main branch). It seems to work very well for my purposes for now, and I'm more than happy to have some sort of commenting possibility, but we'll see if in the future I decide on some other solution (Comm(ent|it) doesn't support anonymous commenting and you're still trusting your non-anonymous information with unknown sources, that is, me).</p>

<p>But in the meantime, here we go. I'll be using this site as a kind of diary, linking interesting things from the internet and sharing my viewpoints on anything. All opinions herein are mine, and feel free to comment!</p>

<p> As a first post, check out this video of a guy who built his own VR set with multiple Kinects. It might be a far cry from what companies like Macig Leap <a href="http://www.wired.com/2016/04/magic-leap-vr/">promise</a> but it's DIY and as a proof of concept quite staggering.</p>
<div style="margin: 0px auto; text-align: center;">
<iframe width="320" height="192" src="https://www.youtube.com/embed/Ghgbycqb92c" frameborder="0" allowfullscreen image-center></iframe>
</div>
