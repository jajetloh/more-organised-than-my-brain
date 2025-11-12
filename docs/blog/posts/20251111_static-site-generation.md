---
tags:
date: 2025-11-11
toc: true
---

# Static Site Generation

What better way to kick this off than to talk about Static Site Generation, in particular my experience thus far.

## Mkdocs

As of the time of writing this, this blog is rendered using [Mkdocs](https://www.mkdocs.org/)! Specifically with [Mkdocs Material](https://squidfunk.github.io/mkdocs-material/). Looks a lot nicer than just Mkdocs. Also looks plenty customisable as the default still looks too close to [Bootstrap](https://getbootstrap.com/) for my liking.

Mkdocs is Python-based, so easy for a wider audience to learn to use. Lovely!

I'm trying to see if we can kick off a shared documentation project at work using Mkdocs Material as well.

Easy enough to hook up up a deployment pipeline as well with GitHub Actions.

Classic, proven, and just works. Good ol' reliable.

## mdBook

If Mkdocs is the good ol' reliable, Mdbook is the cool new kid on the block, rolling up in a ferrous electric vehicle (because emissions aren't cool) that goes 0 to 100 at C-like speeds. By that I mean that mdBook is based in Rust, so of course I love it.

It's incredibly clean out the box, has like 6 different theming options, and a *really good* built-in search. I'm using it for the [QuokkaSim Book](https://jajetloh.github.io/quokkasim-book/), naturally also because QuokkaSim is a project in Rust.

I don't know how difficult it is to customise, but also I don't really care at this point, it already looks so clean, so fast, so smooth that looking for a customisation hasn't really crossed my mind with mdBook.

## Hugo

I've known about Hugo for a while now, since [Fireship's "Hugo in 100 Seconds" video](https://www.youtube.com/watch?v=0RKpf3rK57I). And I've wanted to have an excuse to try Go. It boasts being fast - and from my experience with following their quick start, the build is indeed very fast.

But I feel like installing themes using Git submodules is a little weird. And the theme I did try wanted me to delete a bunch of stuff and copy a bunch of files in. Then I tried for a while to figure out how to replace the provided logo but couldn't. My experience just wasn't very intuitive - a far cry from what I now realise is the seamless experiences provided to me by Mkdocs and mdBook.

## So...

Yeah, I'm trying out Mkdocs Material for this blog (as of the time of writing), though I'm also using mdBook for the QuokkaSim Book. Here's to more blog posts!