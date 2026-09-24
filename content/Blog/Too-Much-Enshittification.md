+++
date = 2026-06-07T01:14:54-08:00
draft = true
title = 'Too Much Enshittification (A Rant)'
weight = 10
[params]
  author = 'Hadi Al Hassan'
+++

Last year we had multiple Cloudflare and AWS outages, which shed light on the term **Enshittification**, which can be used to describe the phenomenon of Platform Decay, the longer it lives. Wikipedia defines it as how companies attract users with high performance and quality services, which then get degraded over time for the sake of business customers, and eventually get degraded for both user and business customers for the sake of profits.


Reminds you of certain AI companies and their latest models, dont they?


Well, I like to also add to those reasons another: lack of care for the craft, and good software standards.

Before 2022, you had to write code yourself, that worked, and passed tests, for you to be able to merge and ship it.
Now, with these non-deterministic compilers we call ChatGPT and Claude Code and others, anyone can "write" that visually does what it should do, and causes 50 bugs and regressions along side it.

> And why would we care if code is written correctly and tested, we'll make money nontheless.

Is probably the thought of Big-Tech companies nowadays, companies like Meta, Microsoft, Meta seem to be willing to bloat their applications with bugs without a care in the world.

I Have logged (and submitted) over the past few months, several bugs (behavior and UI) I noticed in WhatsApp, Instagram, and Tiktok:

- Several Year old voice notes being played in your WhatsApp chats randomly after playing some other voice note with that contact.
- Lag when playing voice notes (you play one, and it should switch to the next one after making a sound, it currently goes mute for a second instead of playing the sound and you lose a second of the voice note).
- No padding in the message bar between the text and send button on Instagram when the text is RTL
- TikTok Audio keeps playing after switching apps or exiting it momentarily, leading to much discomfort.

Bugs are a natrual part of any software, my issue is with the lack of resolving them, I submit multiple bug reports, and the tickets are either unresolved or closed. And we can't argue that maybe these companies have too many tickets submitted they need time to clear them, they have replaced customer support agents with AI agents, that fail to route you to customer support even after you request to.


When AI came out, I expected the FAANG Companies (now more letters added to the list)


The purpose of this rant is to draw attention to how software companies are willingly shipping bad code, and ignoring good software practices, leading to more enshittification.

References:
- https://www.merriam-webster.com/slang/enshittification
-  https://en.wikipedia.org/wiki/Enshittification