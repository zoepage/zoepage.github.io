One week ago, I’ve started my job as Web Compat Engineer at Mozilla and it’s been wonderful so far! 
It’s a very welcoming place here in Berlin and my team is superb! So, summed up in one GIF?

<img src="https://media.giphy.com/media/10uJ0IFxlCA06I/giphy.gif" alt="Hands make a heart" />

When people ask me, what I actually do, the conversations mostly go like this… 

**A: “So, Web Compat Engineer? Huh... What do you do exactly?”**  
B: “We make sure, websites work in the same way on every platform.”  
**A: ”So, I can report a bug when I find one?”**  
B: ”Yes, please! Just hop over to [webcompat.com](https://webcompat.com) and let us know, what you’ve found! We’ll help to fix it.”  
**A: “Oh, great. So you can fix my broken website, right?”**  
B: “Well, it depends… Is your bug appearing in one browser, but not another? Then it is a web compact bug and you should totally report it.”

<img src="https://media.giphy.com/media/c4Nc0v0g15g9G/giphy.gif" alt="Jake thinks this is interesting." />

## What is a Web Compat bug? 

If you find a bug on a web site, just ask yourself… Is this happening just in one browser or in all of them? 
**If it’s in more than three common browsers, please report the bug to the website.** They’ll be happy about some good pointers how to reproduce the bug and which system / browser you are running etc, because everyone deserves good bug reports. ;)

**If this is happening in just one or two browsers, this is pretty likely a Web Compat bug, which you should report over at [webcompat.com](https://webcompat.com).** 
This could be e.g. a prefix the website is using, but just for one browser and others are left out. Maybe the prefix isn’t even needed anymore. Or the specs are not implemented in a correct way into the browser. (Specs just say *what* should be implemented, but not *how*). 


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


# Thank you <3
