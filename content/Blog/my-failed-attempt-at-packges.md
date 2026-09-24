+++
date = 2026-09-24T01:14:54-08:00
draft = false
title = 'My (Failed) Attempt at Freelancing, And (Successful) at Completing a Project for Once.'
weight = 10
[params]
  author = 'Hadi Al Hassan'
+++

A few months ago, I wanted to try and see if I could make money from freelancing and apply what I learned from my work in my personal projects. It did not go how I was expecting it to, and instead of sulking, I used it as a chance to expand my portfolio, share any lessons learned, and dip my toes in the open source library pool ( even if it was built with AI ) 


I noticed that some of the restraunts in my area had old 2015-ish menu sites, the ones that come with their POS softwares or from those companies that take an annual fee for hosting your menu on their domain. So I thought why not make a better one for those restraunts, at a cheaper cost than those websites, and I get experience in return, and try some new libraries along the way.

And while I did succeed in creating the menu site (for 3 different restraunts), and extracting the code to a shared library I can reuse for later times, I did not succeed in selling them to the restraunts I created them for.

One place closed due to finances before the deal went through, the second place had multiple people offering them websites, and the third already had a website in development, so much so they were not interested in taking the site and domain for free.

It was a bit discouraging, I mean I spent time on those websites, adding more and more features to give myself a better selling point for the restraunt owners, I got feedback from various people, and iterated till I had something I was satisfied with, and...., I ended up getting rejected. 

But it wasn't all frowns. 

On the bright side, I for once completed a project without scope creeping, I started with a small POC generated with AI, using one HTML page, and kept changing details, till I had an idea of how I wanted the experience to be, and how a user would like to see the menu, and when I was satisfied, I scaffolded it onto a React Project, which became the first restraunt website, along with potetial client #1, I copied and redid the same website idea for potential client #3, and along the way I was fixing seperate bugs found in each website, which led to extract the shared code to a common folder, and named it `restraunt-kit` which gave me a resuable template for any potential client later, all I had to do was have Claude extract their current menu items, prices, and pictures with a script it made, generate a color palette for their brand, and I could have something I can make money off of quick and easy every time.

More importantly, it finally gave me a reason to ship something as an NPM package, and open source it, in the hopes it will be critiqued harshly, from other devs and product people, and help me learn something new and improve. And i figured if another dev with an AI sub got to use this work and make some money himself selling a client, I'd be happy the code ended up having some use.

And I now have a new website, [www.packages.hadialhassan.dev](https://packages.hadialhassan.dev/h) (whose design was shamelessly copied from kolejain.com 's website A Web Designer  I follow),  where I can share any new projects I end up not scrapping and learned something from.

Another thing I like is I took the courage of publishing these, the library, the website, this article, Half-baked. I don't like publishing half baked material (which is why this blog has been stale since last year, why my university projects had less features, and why it took forever for me to submit a report, right before the deadline) I'm a perfectionist. I realized if i kept waiting for time to make them polished, I would never publish them, now with them out in the open, to the eyes of everyone, I will be more compelled to revisit my work, iterate over it, and keep polishing until it is of the quality I like anything with my name on to have.


There were other lessons learned along the way too, like how to sell your software to clients, what angle to play, how to approach things from a user's perspective, how to take things slow and not jump the gun on some decisions (like buying domains for clients that didn't even confirm they wanted a new website to begin with).


Feel Free to check out the websites for yourself, and if you would like to purchase the domains i bought for them feel free to contact me :)

- www.soubras-lb.com
- www.munchease-lb.com


- Checkout Kole's youtube channel, the guy is cracked when it comes to Web design https://www.youtube.com/channel/UCR6MXpfFWbOpNlxuhWCBV_A