---
# the default layout is 'page'
icon: fas fa-info-circle
order: 5
---

<!-- > This site is highly WIP and may contain partially improper information and inconsistent design.  
Thanks for understanding.
{: .prompt-warning } -->

## About the website

*I'm not sure how did you find this place, but since you did, welcome!*  
I've created this website to help you learn something interesting (or not) about me. You can get all essential information about me on this page, or check the [links at the bottom](#links) in case if you just want to contact me. While this page provides you some general facts from my life, the blog posts will be bringing my voice into the public with more limited scope, yet detailed thoughts.

> To get basic information about me, check the [Personal info](#personal-info) section.
{: .prompt-info}

---

## Bio

My name is Alt, but I'm also known as Asriel or Azzy. I'm a second-year university student who is studying software engineering.  
My hobbies are programming, text roleplaying, and a lil' bit of gaming. I used to play a lot, but now I can't say I'm a real gamer, rather just admiring video games as a culture.  
I support free and open-source software *(although still using that frickin' glassy piece of proprietary blob named Microsoft Шindoшs)*, enjoy skeuomorphic design languages like Windows Aero (not extremely plain modern ones are also good, Fluent Design for instance) and love retrocomputing in general.  

I can code in Python almost fluently, have a little experience with C# and Lua, and currently trying to learn HTML/CSS/JS. Also considering learning either C or Rust.  
Occasionally I draw things that pop up in my head, but this piece will tell you their average quality:  
![Poorly drawn Asriel in Among Us style with a white soul](https://cdn.discordapp.com/attachments/713481949896900622/1013586971249082418/asrielus.png){: .w-25 }
*yes, this was drawn in MS Paint*

I wish I could draw better, but I'm too lazy to learn it. But either way, the current profile picture was drawn by me, and I'm a bit proud of it. If you're brave enough, you can check out [my other "artworks"](../art-stuff).

My favourite video games (or simply games I still play sometimes) are:

- Deltarune and Undertale,
- Minecraft (best below 1.9, acceptable prior to 1.19.1),
- C&C: Renegade,
- Half-Life/Portal series,
- World of Tanks.

## Personal info

- **Name:** Alt/Asriel/Azzy.
- **Age:** 18 years old.
- Gender:
: 
```py
>>> print(A1Asriel().gender)
AttributeError: 'A1Asriel' object has no attribute 'gender'
```

- **Pronouns:** any (excluding neopronouns).
- **Timezone:** UTC+3 (Europe/Moscow).  
  <span id="time-in-utc3"></span>

<script>
  text = '<span><b>Current time here:</b></span> <span id="time"></span>';
  document.getElementById('time-in-utc3').innerHTML = text;
  document.getElementById('time').innerHTML = new Date().toLocaleTimeString([], { timeZone: 'Europe/Moscow' });
  setInterval(() => { document.getElementById('time').innerHTML = new Date().toLocaleTimeString([], { timeZone: 'Europe/Moscow' }); }, 1000);
</script>

## Projects

### Discord bots

| Name                                             | Status                          |
|--------------------------------------------------|---------------------------------|
| [**OpenWorld**][ow-source]                       | Discontinued[^rebrand-to-abl]   |
| [**AsrielBot Legacy**][abl-site][^closed-source] | In active development (β-stage) |
| [**Anastellos Engine**][ae-source]               | In active development           |
| **AsrielBot**                                    | *Planned(?)*                    |

### Other stuff

| Name                                             | Status                          |
|--------------------------------------------------|---------------------------------|
| [**GTA-3000**][gta3k-source] | Discontinued (joke project) |
| [**Personal website**]({{ site.url }}) | Active

[gta3k-source]: https://github.com/A1Asriel/GTA-3000
[ow-source]: https://github.com/A1Asriel/OpenWorld
[abl-site]: https://a1asriel.github.io/AsrielBot-site
[ae-source]: https://github.com/A1Asriel/anastellos

## Devices

> *Devices specs have been moved to a [separate page](../devices)!*

## Links

<!-- - [**Personal Discord server**][discord-invite]  
  **Discord username:** A1Asriel#8203 -->
- [**Twitter**][twitter-link]
- [**Guilded**][guilded-link]
- [**GitHub**][github-profile]
- [**YouTube channel**][youtube-link]
- [**Steam**][steam-link]

<!-- [discord-invite]: https://discord.gg/{{ site.discord.invite }} -->
[twitter-link]: https://twitter.com/{{ site.twitter.username }}
[guilded-link]: https://guilded.gg/{{ site.guilded.username }}
[github-profile]: https://github.com/{{ site.github.username }}
[youtube-link]: {{ site.youtube.url }}
[steam-link]: https://steamcommunity.com/id/{{ site.steam.username }}

## Footnotes

[^rebrand-to-abl]: AsrielBot Legacy is a successor to this bot.
[^closed-source]: The source code is not yet opened.
