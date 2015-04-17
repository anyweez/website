+++
date = "2015-04-08T01:01:56-07:00"
draft = false
tags = ["neckbeard", "website"]
title = "The joys of Hugo, my new blogging platform"
+++

I recently re-launched my website, which pivots primarily around my personal blog. For years I've used [Wordpress](http://www.wordpress.org) to manage my own site, which is great for what it does but frankly overkill for what I need, with a bunch of administration menus, a database, plugins, etc. I've got a lot less time to spend administering my own site than I did in college, so what I want is a simple, fast, secure, and rock-solid site that has very few parts that can break, even if it means I have to trade that off for a bunch of bells and whistles. 

Hugo is exactly what I want. Thank you, Hugo creators, for making such an awesome tool.

From a technical perspective, there are two different approaches a website can take to provide a web page back to the user: it can provide a _static_ page, meaning one that is generated once and then the same file is served back to everyone, or it can be _dynamic_, meaning one that is pulled together when the user requests the web page. Hugo is a tool to do the former, and Wordpress is a tool to do the latter.

Here's a quick list of the trade-offs I concerned before switching to a static site, from both the perspective as the writer and the server administrator:

- Advantages of static
	- **The site becomes much, much faster** because nothing needs to be produced on the fly. All of the pages are generated one time in the middle of the night and since they rarely ever change, I can just return the same page back to everyone who asks.
	- **Really simple setup.** No databases are required and the machine serving the web site can be pretty bare bones. I use a Raspberry Pi that I bought for $25 and can handle way more traffic than I could when I was paying $8 / month to run Wordpress.
	- **I don't have to be online** to write blog posts. I'm actually on a plane as we speak, and since I can edit the post on my local computer and submit it easily to my blog later there's literally no difference in how I work when I'm online and when I'm offline.
	- **No security concerns.** Dynamic sites are actually executing code on the user's behalf (which is what makes it so powerful, but also slow), and when code is running it usually means there's a way for someone to bend that code to do their bidding. Static sites don't do this, and have very few security issues compared to dynamic sites.
- Disadvantages of static
	- **Can't support user-specific features** like logging in or commenting. Fortunately in my case I'm trying to show the same thing to everyone so I don't miss out on much here.
	- **No notion of "plugins"** in the Wordpress sense so certain features are much more difficult or impossible to add to a static site.

Historically static pages have been used whenever the page is the same for everyone, and dynamic have been used whenever the page varies depending on who's asking for it. For a number of reasons, some valid and some less so, blogs and other sites with relatively simple content have drifted in the dynamic direction over the past decade or so even though many of them can do everything they want with a static site with fewer headaches. At some point I got tired of the maintenance required to keep my dynamic site online and started looking for alternatives, but it's only recently that Hugo has come along and hit the nail on the head.

For those out there writing their own blogs and looking for something to simplify down to focus on writing, I'd encourage you to check out Hugo. I love it and have no plans of going back!