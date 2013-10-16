---
layout: everyday-text
title: Fixing Broken Facebook Shares
date: 2013-10-15
---

You know when you try to share a link on Facebook and the correct thumbnail or description or title doesn't show up? It happens to me every now and then. I end up reloading the page a couple times, or maybe trying a different browser hoping it'll trigger Facebook into pulling the right data.

<img class="img-wide big-box-shadow" src="/assets/2013-10-15-fixing-broken-facebook-shares-1.jpg" alt="Facebook share thumbnail and description not working">

What's happening is that Facebook scrapes pages when people share them. It grabs images and meta tags and uses that data to auto-generate the thumbnail and description. But it doesn't scrape the page every time someone shares it. It caches what it scrapes the first time and then pulls from its own cache when someone else shares the same page. The problem is that sometimes its cache doesn't have the correct or most up-to-date data.

The way to fix this is to trigger Facebook to re-scrape the page. Think of this like clearing the cache on your browser.

All you have to do is use the [Facebook Developers Debugger tool](https://developers.facebook.com/tools/debug). Follow that link and paste in the URL you're trying to share. That's it. The debugger will re-scrape the site's data. Now go back and share the URL. The thumbnail, description, and title should now work.

<img class="img-wide big-box-shadow" src="/assets/2013-10-15-fixing-broken-facebook-shares-2.jpg" alt="Facebook share thumbnail and description fixed">