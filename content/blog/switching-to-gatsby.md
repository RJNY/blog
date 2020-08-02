---
title: Gatsby + Cloudflare Workers = New Blog!
date: 2020-07-15
description: none
---

## Hello Jekyll + Github Pages

Jekyll is a simple static site generator. It is "blog-aware" and makes it very simple to write a
blog site quickly. It was written in Ruby and was very easy to get a personal blog up quickly.

I originally come from a Ruby background so Jekyll was appealing to me as a beginner.
[My first blog](https://richardmacias.net/) was built with Jekyll.

Github Pages makes it dead simple to host one (and only one) static site. My personal blog was
deployed using Github Pages. It is incredibly easy and beginner friendly. All that's needed to
deploy your site is to push it to your github branch and press a button that says "Github
Pages". So easy!

## Hello Cloudflare

Cloudflare lets you put _any_ website behind it as a proxy and comes with a lot of nice things for
free. For a static website like mine, Cloudflare offered to cache the entire site making it much
faster than it was before, https enabling and ddos protection.

I didn't have to change anything with my legacy at all. Cloudflare was enabled and I never had to
think about it again.

## Hello Gatsby

GatsbyJS came along and perfected a React blog that is blazing fast and efficient. Without getting
into too much detail, it is arguably
way faster than Jekyll which has to do a server call for all navigation while Gatsby does not.

## Hello Gatsby + Cloudflare Workers

Cloudflare Workers allows you to run plain-old-javascript on Cloudflares edge network. This is a
network of machines distributed across hundreds of locations across the globe. Each of these
machines host an instance of my site which can reach an audience around the globe faster than a
single server ever could.

## Goodbye Jekyll + Github Pages

I love how my jekyll site looks, but its performance has been showing its age and I won't miss
struggling with jekyll upgrades breaking my local development.

I am happy I get to play around with React on my weekends. It gives me an opportunity to quickly
spin up applications for friends/family and customers. I haven't been much of a blogger in the past,
but hopefully this is something else I can become better at over time.
