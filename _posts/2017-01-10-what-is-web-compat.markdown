One week ago, I’ve started my job as Web Compat Engineer at Mozilla and it’s been wonderful so far! 
It’s a very welcoming place here in Berlin and my team is superb. 

When people ask me, what I actually do, the conversations mostly go like this… 

A: “So, Web Compat Engineer? Huh... What do you do exactly?” 
B: “We make sure, websites work in the same way on every platform.” 
A: ”So, I can report a bug when I find one?” 
B: ”Yes, please! Just hop over to [webcompat.com](https://webcompat.com) and let us know, what you’ve found! We’ll help to fix it.” 
A: “Oh, great. So you can fix my broken website, right?” 
B: “Well, it depends… Is your bug appearing in one browser, but not another? Then it is a web compact bug and you should totally report it.”



## What is a Web Compat bug? 

If you find a bug on a web site, just ask yourself… Is this happening just in one browser or in all of them? 
**If it’s in more than three common browsers, please report the bug to the website.** They’ll be happy about some good pointers how to reproduce the bug and which system / browser you are running etc, because everyone deserves good bug reports. ;)

**If this is happening in just one or two browsers, this is pretty likely a Web Compat bug, which you should report over at [webcompat.com](https://webcompat.com).** 
This could be e.g. a prefix the website is using, but just for one browser and others are left out. Maybe the prefix isn’t even needed anymore. Or the specs are not implemented in a correct way into the browser. (Specs just say *what* should be implemented, but not *how*). 

## But why do we need Web Compatibility, if I can make it work by hacking things!?
Remember the clash of WebSQL and IndexedDB? The specs just described *what* should be implemented, so browser vendors came up with different version which were incompatible? Just for clarification, to be accepted as a full standard, a spec must be implemented in the same way by at least 3 different browser vendors. So, suddenly there was this [mess](https://www.raymondcamden.com/2014/09/25/IndexedDB-on-iOS-8-Broken-Bad/) and you either had 2 different implementations or you used localStorage and ignored the web database. After years of discussions, IndexedDB became a standard, WebSQL was depricated and IndexedDB was implemented in Safari (in Sept. 2016). http://caniuse.com/#search=indexeddb



## Why should I report a Web Compat bug? - Benefits of reporting 

- Not just visibility of bug, but also chance it will be fixed 
- seeing how many developers are truly annoyed by this bug (will be prioritized higher by browser vendors) 



## Why does it matter? 
We need to stop hacking things. Clean code is valuable for everyone. Not just because updating hacked code is hard and you get yourself in a bigger mess everytime you do something. But also, because it takes us forever to find those browser quirks and learn things, we shouldn't need to know. Just think about how much time and frustration you had to go through, while you fought with those type of bugs?!

We should have a web that works for everyone. Make it not just user, but developer friendly.


## How can I help beyond just reporting bugs? 
With reporting, you already did the biggest part on helping make the web accessible for everyone.
But you can also help with checking out bugs, finding solutions or share your knowledge... You can find more about the how at https://webcompat.com/contributors.


# Thank you <3
