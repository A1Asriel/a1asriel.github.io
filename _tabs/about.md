---
icon: fas fa-info-circle
order: 6
---

## About the website

Welcome to my humble GitHub Pages-hosted personal website-slash-blog!  
I've created this place to socialize a little and make it easier to learn something about me, in case you're interested for some reason. If you only need my contact information, you can just jump straight to the [links](#links) at the bottom of the page. While it already provides you with more than enough information, the blog posts will be bringing my voice into the public with a more limited scope, yet detailed thoughts, if I ever come out of my eternal hibernation and actually bring myself to writing some.

> The essential info is located in the [Personal info](#personal-info) section.
{: .prompt-info}

---

## About me

I'm a third-year university software engineering student, who is mostly known as Alt and A1Asriel on the Internet. My hobbies include programming, text roleplaying, and a bit of gaming. Even though I used to play video games much more, I still do it from time to time to this day.  
I prefer free and open-source software (still using the "Windows" bloatware though), clean and modern UI design languages such as Frutiger Aero or Microsoft Fluent, but enjoy retro aesthetics as well.

My programming skills: nearly fluent in Python, have got some experience with C, C#, HTML/CSS/JS, Lua, and GDScript.  
I'm definitely not an artist, but occasionally I draw things that pop up in my head. Before you get too excited, I will show you this little piece which might tell you their average quality:  
![Poorly drawn Asriel in Among Us style with a white soul](/assets/img/art/asrielus.png){: .w-25 }
*yes, this was made in MS Paint*

I wish I could do better, but I'm too lazy to learn. If you're brave enough, you can check out [my other "art"-works](../art-stuff). The page also features some 3D-renders and edited photos.

My favourite video games (and other games I still play to this day) are:

- Deltarune and Undertale - these two obviously are my favourites of all time,
- Ultrakill - got addicted to it pretty recently,
- C&C: Renegade - the game of my childhood,
- Half-Life and Portal series - love their linear yet exciting gameplay,
- Minecraft - don't really play it anymore (since 1.9), but follow the updates.

## Personal info

- **Name:** Alt/Asriel/Azzy.
- **Age:** 19 years old.
- Gender:
: 
```py
>>> print(A1Asriel().gender)
AttributeError: 'A1Asriel' object has no attribute 'gender'
```

- **Pronouns:** any (no neos).
- **Languages:** Russian (native) and English (B2).
- **Country of residence**: Russian Federation.
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

| Name                                   | Status                        |
|----------------------------------------|-------------------------------|
| [**OpenWorld**][ow-source]             | Discontinued[^rebrand-to-abl] |
| [**AsrielBot Legacy Beta**][abl-site]  | Active/In development         |
| **Proelefsi Project Alpha**[^proelefsi]| Active/In development         |

### Websites

| Name                                   | Status                    |
|----------------------------------------|---------------------------|
| [**Personal website**]({{ site.url }}) | Active                    |
| [**«WэК!» (nostalgic WoT mod series) website**][wek-site] | Active |

### Other stuff

| Name                               | Status                     |
| [**Anastellos Engine**][ae-source] | In semi-active development |
| **Epamenos Project**[^epamenos]    | Planned/Early development  |

[ow-source]: https://github.com/A1Asriel/OpenWorld
[abl-site]: https://a1asriel.github.io/AsrielBot-site
[ae-source]: https://github.com/A1Asriel/anastellos
[wek-site]: https://wotclassic.github.io

## Links

- [**Personal Discord server**][discord-invite]  
  **Discord username:** A1Asriel#8203
<!-- - [**Twitter**][twitter-link] -->
<!-- - [**Guilded**][guilded-link] -->
- [**GitHub**][github-profile]
- [**YouTube channel**][youtube-link]
- [**Steam**][steam-link]

[discord-invite]: <https://discord.gg/{{ site.discord.invite }}>
<!-- [twitter-link]: https://twitter.com/{{ site.twitter.username }} -->
<!-- [guilded-link]: https://guilded.gg/{{ site.guilded.username }} -->
[github-profile]: <https://github.com/{{ site.github.username }}>
[youtube-link]: <{{ site.youtube.url }}>
[steam-link]: <https://steamcommunity.com/id/{{ site.steam.username }}>

## Footnotes

[^rebrand-to-abl]: AsrielBot Legacy is the direct successor of OpenWorld.
<!-- [^closed-source]: The project is using proprietary closed-source code. -->
[^proelefsi]: Proelefsi Project (aka BendyBot) is a knowledge base bot for the «WэК!» Discord server.
[^epamenos]: Epamenos Project is an upcoming successor of Anastellos Engine.
