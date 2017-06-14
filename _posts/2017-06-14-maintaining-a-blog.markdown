---
layout: default
title:  "Yet another tech blog"
date:   2017-06-14 14:43:00
categories: main blogging
---

# Maintaining a blog
## Writing for self
Every day, I add an entry in my personal journal. Whether it is to keep track of my press review of the day (incoming article about that) or to put some distance with my day and highlight what I've learned, I find necessary to write down a summary of my day.

It is way harder to hide behind excuses when writing. On the opposite, questioning what is on the screen feels natural. It is almost as reading someone else's writing. The lack of arguments pops out immediately. The lack of clarity as well. In my journal, it feels impossible to have an opinion without presenting arguments.

## Making it public
I do not wish to make my private journal public. Instead, I am planning on compiling the most important notes into blog articles. The point is not to expose myself fully. I am making public the technical work I have done. As an example, it can be an article about how I set up a software forge using Gitlab and Docker. I also plan on exposing how I organise myself.

## Letting others judge
I think that making articles public is a strong motivation for working with care, even when experimenting. When I am acquiring new skills, I need to understand it clearly to be able to talk about it. It also helps structuring more my knowledge to express it efficiently.

Being under the critics fire requires to be able to put the feedback in perspective. Helpful advice will probably emerge, as I do not state I am an expert, but some trolling will definitely happen. We are on the internet after all.

# How and where to host
## Jekyll
I initially thought that I would maintain a static blog which would be no more than a plain HTML page, on the model of the [wickedly fast loading page][1]. What I absolutely needed was a secure and fast loading page.

Then I realised that if I wrote blog notes regularly, I would need to archive it. Archiving means pagination. Pagination means boring and repetitive for humans. Boredom and repetitiveness mean mistakes. Uh.

A few moments of googling later, I discovered [Jekyll][2]. To put it simply: you write markdown, Jekyll makes a static blog out of it. Cool. Having a quick look at [Jekyll's skel][3], I found it quite explicit, and decided to give it a try.

GitHub Pages
Oh but wait, why host it myself if I can have free and secure hosting? Good news, [GitHub][4] offers the service [GitHub Pages][5] which can basically consist of… free hosting of your Jekyll blog. Sweet. It even supports [custom domains][6]!

More on how I set it up in a next article.

[1]: https://varvy.com/pagespeed/wicked-fast.html
[2]: https://jekyllrb.com
[3]: https://jekyllrb.com/docs/structure/
[4]: https://github.com
[5]: https://pages.github.com/
[6]: https://help.github.com/articles/quick-start-setting-up-a-custom-domain/