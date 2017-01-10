---
published: false
title: Why do we need Web Compat
layout: post
tags: [mozilla, firefox, web, compat, compatibility, webcompat.org]
categories: [mozilla, web, compat]
---

Last week, I published the first part of this blog post called [What is Web Compatibility?](https://zoepage.github.io/2017/01/10/what-is-web-compatibility.html), which explained what it is and how you can identify a web compat bug.

## But why do we need Web Compatibility, if I can make it work by hacking things!?
Remember the clash of WebSQL and IndexedDB? The specs just described *what* should be implemented, so browser vendors came up with different version which were incompatible? Just for clarification, to be accepted as a full standard, a spec must be implemented in the same way by at least 3 different browser vendors. So, suddenly there was this [mess](https://www.raymondcamden.com/2014/09/25/IndexedDB-on-iOS-8-Broken-Bad/) and you either had 2 different implementations or you used localStorage and ignored the web database. After years of discussions, IndexedDB became a standard, WebSQL was depricated and IndexedDB was implemented in Safari (in Sept. 2016). http://caniuse.com/#search=indexeddb

<img src="https://media.giphy.com/media/wpoLqr5FT1sY0/giphy.gif" alt="Dog typing on keyboard." />

We need to stop hacking things. Clean code is valuable for everyone. Not just because updating hacked code is hard and you get yourself in a bigger mess everytime you do something. But also, because it takes us forever to find those browser quirks and learn things, we shouldn't need to know. Just think about how much time and frustration you had to go through, while you fought with those type of bugs?!

We should have a web that works for everyone. Make it not just user, but developer friendly.

## Benefits of reporting 

You might assume the bug was already reported, because the other developers do that all the time, right? 
Well... most likely? No. If you ask at a meetup, conference or whereever you meet other developers how many of them reported a bug before, 1-2 hands will go up. *If* you're lucky!

And what if it was already reported? There is no dragon standing in front of the bug tracker and eat you alive, just because you did it... 

<img src="https://media.giphy.com/media/SIClNyzUQv5Vm/giphy.gif" alt="Cute dragon scratching himself." />

(Okay, maybe just a very cute one, who is nice and wants to give you a hug!)

The more developers report bugs, the higher is the chance to get all of them covered. PLUS it makes specific bugs so much more visible and the fact how annoyed developers are by this one bug, so browser vendors will prioritize it higher and fix it sooner. 

Your experience, knowledge and voice is what is the most important thing. Browser vendors need you! Your input. You are the ones building the web, shaping up the web. 

## How can I help beyond just reporting bugs? 
With reporting, you already did the biggest part on helping make the web accessible for everyone.
But you can also help with checking out bugs, finding solutions or share your knowledge... You can find more about the how at https://webcompat.com/contributors.


<img src="https://media.giphy.com/media/tnivTK2URZm7e/giphy.gif" alt="Care bears sending hearts out of their bellies." />

**Thank you <3**

<small>*This is the second part of a two part blog post.*</small>
