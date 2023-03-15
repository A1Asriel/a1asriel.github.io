---
title: The future of AsrielBot, a new brand, and other changes
date: 2023-03-09 18:35:00 +0300
tags: [discord, internet, open-source, asrielbot]
---

I'm aware this isn't exactly the post some of you have been waiting for, but it's not an easy task to write a huge wall of coherent text, at least for me. So I've decided to write about what's on my mind right now, before it's gone.  
But either way, as the time passes - things change, and therefore some big changes are coming to my projects as well.

## The new management

The most important upcoming change for all of my projects is the foundation of a new company. While it may not seem like a big thing, this change will allow me to gather more people to work, and the projects won't be associated solely with me anymore, therefore prolonging their life in case of if I stop working on them.

## AsrielBot or not?

Since the very beginning of [AsrielBot](https://a1asriel.github.io/AsrielBot-site)'s development, it was renamed two times: from "OpenWorld" to "AsrielBot" and from "AsrielBot" to "AsrielBot Legacy". The first change was caused by the semi-forced decision of closing the source code (it's wasn't that "open" anymore), while the second one was made after setting a new milestone of remaking the bot from ground up on a new engine. The old engine was named "[Anastellos](https://github.com/A1Asriel/anastellos)", which stands for "stale" in Greek (at least that's what Google Translate said), except for the spelling is slightly screwed up.

A lot of time has passed, and literally 0 lines of code for the new engine was written. Yet the "stale" engine has been developing over time, turning into a pretty powerful tool for bootstrapping Discord bots of different kinds. It's not that robust or stable, but it does its job well, it's slowly transforming into what once was just an idea. It already has most of the features that were planned to be implemented in the new engine. Besides, there are a lot more new major milestones and goals to reach, for example, Guilded API support for making crossplatform bots easily. There's simply zero reason to spend time to recreate something that already exists when we can expand its features further instead. So maybe the "Stale Engine" isn't that stale after all.

And let us come back to the actual bot. The appending of "Legacy" wasn't the most right thing to do, considering there was no working prototypes at the time. But we won't simply remove this suffix.

## A new bot

Right now AsrielBot Legacy is a playground for testing the capabilites of Anastellos Engine, therefore it gets almost completely unrelated features. At first it was just an RNG bot for roleplaying, later on it got other features that were more or less related to its original purpose. But the latest updates have given it some almost completely unrelated functions, such as moderation tools and reaction roles. And if we sum it all up, there's little to no relation to the original character, who it was called after.  
And so I have decided to split this bot into two separate ones sometime during the further development.

![](https://cdn.discordapp.com/attachments/713481949896900622/1083408191213289532/abl-conversion-light.png){: .light}
![](https://cdn.discordapp.com/attachments/713481949896900622/1083408191464943636/abl-conversion-dark.png){: .dark}

The diagram above should explain you the basics of this conversion. Technically speaking, ABL will be renamed once again, and the rebooted AsrielBot will be hosted as a new instance.

## Change of plans

As it was said above, the bot was open-sourced before. But even after the closure of the source code, it was stated that it will become open again in the future. I hate to say that, but the plans have changed: AsrielBot Legacy will continue developing as a proprietary piece of software until further notice. Anastellos Engine, however, will forever stay in the public domain and will be free to use or change for everyone.

Why is it like this? Well, there are quite a few reasons. The first one is the presence of personal data in the repository. During the early bot development, I haven't been thinking it through and have left a lot of trails of personal data of other users and other secret stuff, necessary for the bot to work at that development stage. I could cut all those traces, but it would take a lot of time and, probably, kill the repository completely if done wrong. Either way, the bot won't be able to boot without that data since it was hardcoded.

I'll be honest with the second reason. There's a prospect of getting some profit from running a proprietary bot with premium features. I didn't want to join the Dark Side, but considering that I'm just a software engineering student who doesn't have a job, this income can be vital for myself.

The third reason is the messages relaying system and a certain not yet announced feature. They both will use a global storage which will be shared between servers for users' convenience. Hosting several instances won't let people connect the same way as if it was hosted on a single instance.

## Current state of AsrielBot

Right now I'm working on the internal structure of Anastellos Engine, which will help me to concentrate more on the actual programming, rather than bothering with other minor things.[^anastellos-commits] Some of the userspace features are also being worked on, and the next update will probably be the most feature-rich one so far. Even simple bug fixes make the experince much more smooth, so the difference is quite big.

I'd say the update is 70% (Anastellos part) / 25% (AsrielBot part) ready, but I can't give you the approximate date of it being 100% ready yet. The university life is too overwhelming by itself, so it's sometimes hard to find some time to work on the bot. But stay tuned, and I will let you know when the update is out!

## Footnotes

[^anastellos-commits]: <https://github.com/A1Asriel/anastellos/commits/dev>