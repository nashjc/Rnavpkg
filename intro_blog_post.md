---
title: "Navigating the R Package Universe"
author: "John Nash, Spencer Graves, Julia Silge, and Ludovic Vannoorenberghe"
date: '2017-07-25'
output:
  html_document: default
---



Earlier this month, we organized a [session at useR!2017](http://sched.co/AypJ) focused on discovering, learning about, and evaluating R packages.

<!--html_preserve--><div><div style="left: 0px; width: 100%; height: 0px; position: relative; padding-bottom: 63%;"><iframe src="https://speakerdeck.com/player/7b74cd7bc78b4ed2837f1d6828c39a96" frameborder="0" allowfullscreen="true" webkitallowfullscreen="true" mozallowfullscreen="true" style="top: 0px; left: 0px; width: 100%; height: 100%; position: absolute;"></iframe></div></div>

<br><!--/html_preserve-->

There are more than [10,000 packages on CRAN](https://juliasilge.com/blog/scraping-cran/), and R users must approach this abundance of packages with effective strategies to find what they need and choose which packages to invest time in learning how to use. Our session centered on this issue, with three themes in our discussion.

## Unification

John has been interested in working on wrappers, packages that call other, related packages for a common set of tasks. With a unified wrapper package, a user only has to learn one API but then can use many different implementations for a certain task. John has been particularly involved in [numerical optimization techniques](https://nashjc.wordpress.com/2016/11/20/choosing-which-method-to-use-for-optimizating-functions/) and presented possibilities there and beyond.

More generally, and as the session revealed in the breakout discussion, there are opportunities to merge either packages
or their functionality. The key issues require, however, human cooperation and some give and take in a realm where egos
can take precedence over the efficiency of the R ecosystem.

There were also suggestions that can be interpreted as the unification of the presentation of packages. Overlapping
with the "guidance" and "search" themes, these ideas seek to provide selective presentations of packages.

## Guidance

Julia explored resources that exist to guide users to packages for certains tasks. R users can turn to long-established resources like [CRAN Task Views](https://cran.r-project.org/web/views/), or newer options under current development such as the [packagemetrics](https://ropensci.org/blog/blog/2017/06/27/packagemetrics) package or the [CRANsearcher](https://github.com/RhoInc/CRANsearcher) RStudio add-in. Julia [organized a survey](https://app.doopoll.co/poll/FGZqTL7vpaaCgpWCM/live-results) before useR about how R users learn about R packages that informed our discussion.

## Search

Spencer has worked on the issue of searching for R functions in his [sos](https://cran.r-project.org/package=sos) package, and led the last section focused specifically on how users can find what they are looking for. Ludovic spoke during this part of our talk about [RDocumentation](https://www.rdocumentation.org/), how it works, how it was built, and how we as a community can use it and contribute to making it more useful.

After the main presentation, we broke out into three smaller sessions focused on these topics for discussion and brainstorming. Both the main session and then our three following breakout sessions were well-attended. We are so happy about the participation from the community we saw, and hope to use people's enthusiasm and ideas to move forward with some steps that will improve parts of the R ecosystem. In the coming weeks, look for three more blog posts on these three topics with more details and ideas on projects. Perhaps something will resonate with *you* and you can get involved!

