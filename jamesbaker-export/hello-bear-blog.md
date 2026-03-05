---
title: 🐻 Hello Bear Blog
slug: hello-bear-blog
published_date: 2026-01-20T21:51:00+00:00
tags: words
publish: true
make_discoverable: true
is_page: false
meta_description: Migrating from Jekyll and GitHub Pages to Bear Blog.
lang: en-GB
---

I recently migrated my blog from a [Jekyll](tab:https://jekyllrb.com/) blog hosted on [GitHub Pages](tab:https://docs.github.com/en/pages) to [Bear Blog](tab:https://bearblog.dev/). _Why?_

## It Just Works™

Good products make complicated things simple.

My girlfriend has almost no experience with HTML, CSS or JavaScript – and she’s made an amazing site: [jessveeb.bearblog.dev](tab:https://jessveeb.bearblog.dev/). That’s because all you need to do to have a great-looking blog is:

1. Read the [Markdown cheatsheet](tab:https://herman.bearblog.dev/markdown-cheatsheet/)
2. Choose from the dozens of ready-made themes

If you want to delve deeper into the weeds of building your own website, you can. The HTML, CSS and JavaScript are there for those who want to play with them, but comfortably out of the way for those who don’t. This is the best way to offer _power user_ features, and Bear Blog does it really well. 

## Image Hosting

A lot of my hobbies (photography, creative coding, collages) involve making images.

I never found a workflow for hosting and sharing images on my Jekyll blog that I was happy with. On Bear Blog, it’s been simple to add images to my site, set up a feed for my [images](/images/), and get a [photo gallery](https://robertbirming.com/photo-gallery/) up and running.

## The [Discovery Feed](tab:https://bearblog.dev/discover/)

I wasn’t expecting to like this as much as I do. I was worried that some of the issues I have with social media would also apply to the Discovery Feed:

- A feed of content
- Chasing likes

However, the feed doesn’t feel like it’s bringing out the same negative emotions that social media did. I’d guess that’s down to the feed being curated. I’ve still turned off all analytics on my site, and this is the first post I’ve done with `make_discoverable: true` that introduces the upvote button. We’ll see how I cope with that.

## Notes on Migrating

I found this really easy. It helped that both use Markdown – and that I only had five posts. The [migration guide](tab:https://docs.bearblog.dev/migrate/) covered everything I needed to make sure my URLs didn’t break.

## The Downsides

The main thing I miss from my Jekyll and GitHub Pages setup is version control. Using [Git](tab:https://git-scm.com/) meant that if I made any mistakes, my changes were easy to revert. Bear Blog doesn’t have an undo button. For now, I’ve made a [Gist](tab:https://gist.github.com/) on GitHub to track my CSS – I just have to keep remembering to copy and paste the code across.