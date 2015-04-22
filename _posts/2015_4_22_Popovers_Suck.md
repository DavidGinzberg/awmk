---
layout: post
title: Popovers suck
---

**tl;dr:**
- Popovers suck
- Popovers are a type of unexpected overlay
- Overlays can be good
- Popovers often include poor accessibility practices


As the title suggests, I think popovers suck (no, not [these](http://goo.gl/jwNR7p)).

For those who aren't familiar, popovers are the tile/window/overlay that shows up on a webpage obscuring the actual
 content (often dimming the background) and preventing you from interacting with the page until you do something with
 the popover or dismiss it. Before we go any further I want to define a difference (at least for the purposes of this
 article) between popovers and overlays. An overlay is anything that covers the content of a page and (usually) prevents
 interacting with the page until the overlay is dismissed. However a popover is a certain type of overlay, specifically
 one which appears suddenly, without being prompted by any user action (or at least unexpectedly caused by something the
 user did, such as scrolling past a certain point in the page). It's often unclear when or why a popover will be or was
 triggered, and sometimes they are difficult to dismiss, but I'll get to that further along in this post.

Overlays, though not universally so, can generally be a good element in a web pages design. Examples of good overlays
 include those that pop up after clicking such links or buttons as "Contact Us", "Change My Security Questions" or
 "Subscribe To Our Newsletter" (A discussion of whether these should be links, buttons, or components of forms would take
 too long here but might be included in another post). It's important to note that these overlays are generally not
 unexpected, because they appear in response to a click action -- even better if there is some indication on the page
 that clicking will cause an overlay.

It's important to note that just because an overlay is expected, doesn't absolve the developer(s) of the site from
 making sure it is well-implemented and easy to use. If you've ever been on a poorly built photography or real estate
 site, you might be familiar with the frustrating experience of clicking on photos, only to find yourself stuck with a
 lightbox (a type of overlay often used for displaying pictures) that won't close until you refresh the page.

Popovers are subject to the same requirements as overlays, even if by their very nature they have already broken the
 first rule about not being unexpected. Many popovers are used as some form of advertisement, whether to get users to
 sign up for a newsletter or to serve an advert for one of the website's sponsors. A cursory search on google shows that
 popovers are generally tough to block with tools like [Adblock Plus](https://adblockplus.org/), and they're certainly
 hard to ignore when they cover up the text or pictures you were looking at a moment ago, which are probably two reasons
 they have become so popular. Unfortunately, to ensure users actually read the content, some websites have made their
 popovers initially difficult to close by disabling keyboard shortcuts to close the popover (like the `Escape` key) or 
 including a timed delay before the close button appears or becomes clickable.
