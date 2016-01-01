---
layout: post
author: Andrew Watts
title: "Starting From Scratch With Octopress 3.0"
date: 2015-12-31T13:53:20-05:00
---

The first version of this post was written in February of 2015. It's finally going
to go up on December 31st. I've been busy and Octopress 3.x is still not entirely
kink free (in fact, I had to run `bundle exec octopress new post "Starting From Scratch With Octopress 3.0"`, because for some reason `octopress new post ...` alone causes a `LoadError` on
`octopress-genesis-theme`) and still doesn't work with Jekyll 3.x.

Long ago I tried starting a blog on GitHub with Octopress 2.x, but I quickly got
frustrated with it because it involved basically forking Brandon Mathis's blog and
tweaking it and hoping nothing upstream conflicted with any changes you made, which
it always did. Or at least for me, but I could've been doing everything wrong. So
I'm just blowing that version of the blog away and starting over now that Octopress
is a set of Ruby gems instead.

Now that I've figured out how to get Octopress 3.x working I'm going to try to
seriously get this blog going. Out of the gate I'm using the default [Genesis theme](https://github.com/octopress/genesis-theme), because [Ink](https://github.com/octopress/ink)
isn't documented well enough yet for other themes to exist or for me
to take a stab at it myself (at least given that I don't have a lot of time to
spend on it). I'm also planning to add Disqus comments in the not too distant future,
once I'm happy with the things are working. I'll also slowly remove all the default
boilerplate Jekyll stuff and personalize it. But I want to get this officially
started before the end of 2015.

Coming soon: a post about who I am and what this blog will be about.
