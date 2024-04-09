![Screenshot of Transformers Animated Blitzwing typing](https://github.com/gigirassy/Nunes-Firefox-Configuration/blob/main/typetypetype.png)
## Behold, my configuration for browsing in Firefox!

I use a configuration focusing on privacy, and extensions that make the internet suck a little less. I take inspiration from [TheFrenchGhosty's LibreWolf configuration](https://github.com/TheFrenchGhosty/TheFrenchGhostys-Ultimate-Firefox-Configuration) and some personal research of mine.

This is definitely not suited for everyone's needs and is not the most private configuration out there, but it's nice for me.

### Privacy extensions
* [ClearURLs](https://github.com/TheFrenchGhosty/TheFrenchGhostys-Ultimate-Firefox-Configuration): Removes tracking from URLs.
* [LibRedirect](https://addons.mozilla.org/en-US/firefox/addon/libredirect/): FANDOM, Reuters, Reddit, Youtube, Quora, Search (I use SearX), Genius, and Medium frontends enabled.
* [CanvasBlocker](https://addons.mozilla.org/en-US/firefox/addon/canvasblocker/): Alters JS to prevent fingerprinting.
* [Cookie AutoDelete](https://addons.mozilla.org/en-US/firefox/addon/cookie-autodelete/): I don't enable autoclean, but clean every four months.
* [Facebook Container](https://github.com/mozilla/contain-facebook): While the actual effectiveness of this extension for separating Facebook activity is debatable, I still find it useful for bypassing paywalls/signup-walls using the containers function.
* [I Still Don't Care About Cookies](https://github.com/OhMyGuus/I-Dont-Care-About-Cookies): Me either.
* [LocalCDN](https://www.localcdn.org/): Delivers some CDNs locally to prevent fingerprinting.

### Extensions that make the internet suck a bit less for everyone
* [Snowflake by Tor](https://snowflake.torproject.org/): Uses some funky trickery to help people access websites in censored countries using your connection at no cost or risk to you. I help 3 people a day on average.
* [AdNauseam](https://github.com/dhowe/AdNauseam/): Extension that uses autoclicking ADs in the background to waste corporations' money, fight surviellence, and as a side effect, support the websites you frequently browse.
* [Wayback Machine Extension](https://archive.org/): I set up Wayback Machine's extension to save any public website I browse using its blacklist feature. It autosaves if a site hasn't been preserved in 7 days. Here's my configuration for blacklisted sites.
```
archive.org*
web.archive.org*
google.com*
*.google.com*
*mail.*
duckduckgo.com/?q=*
discord.com/*
*boards/search*
*bsky*
*flix*
*rentry*
*redlib*
*searx*
*chat*
*annas-archive*
*fandom*
*search=*
*nitter*
```

## Functionality
* Stylus: for user styles.
* Colab Auto Clicker: Because I use Whisper-AI a lot.

## Extra stuff I did
* Modified about:config to allow custom search engines, and set my default to SearX. (specifically, the searx.pro instance)
* Since my CTRL key has been a bit funky lately, I edited my toolbar to have a screenshot button.
* Disabled the ADs and Pocket on the Firefox front page because what the hell.
