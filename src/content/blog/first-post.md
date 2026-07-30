---
title: "Building My Blog with Astro"
description: "How I set up this blog using Astro, a modern static site generator that ships zero JavaScript by default."
pubDate: 2026-07-29
---

## Why Astro?

Astro is a static site generator that takes a content-first approach. Unlike frameworks like React or Next.js that ship JavaScript to the browser by default, Astro renders everything to static HTML at build time.

This means my blog loads incredibly fast because visitors download only HTML and CSS. No JavaScript runtime, no hydration delays.

## What I learned

Setting up content collections in Astro was surprisingly straightforward. You define a schema for your content using Zod, point Astro at a folder of Markdown files, and query them with a simple API.

The best part is the type safety. If I forget to add a required field to a blog post's frontmatter, Astro tells me at build time instead of breaking in production.
