![Screenshot of Transformers Animated Blitzwing typing](https://github.com/gigirassy/Nunes-Firefox-Configuration/blob/main/typetypetype.png)
# Behold, my configuration for browsing in Firefox!

I use a configuration focusing on privacy, and extensions that make the internet suck a little less. I take inspiration from [TheFrenchGhosty's LibreWolf configuration](https://github.com/TheFrenchGhosty/TheFrenchGhostys-Ultimate-Firefox-Configuration) and some personal research of mine.

This is definitely not suited for everyone's needs and is not the most private configuration out there, but it's nice for me.

No software outside of Firefox itself, along with an internet connection, is required to complete this configuration.

## Extensions
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
* [Wayback Machine Extension](https://archive.org/): I set up Wayback Machine's extension to save any public website I browse. It autosaves if a site hasn't been preserved in 7 days. Here's my configuration for sites that won't save.
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

### Functionality
* [Stylus](https://addons.mozilla.org/en-US/firefox/addon/styl-us/): for user styles.
* [Colab Automatic Clicker](https://addons.mozilla.org/en-US/firefox/addon/colab-automatic-clicker/): Because I use Whisper-AI a lot.
* [Simple Translate](https://addons.mozilla.org/firefox/addon/simple-translate/): Not to be confused with the frontend SimplyTranslate. I use this extension to quickly translate non-English text with a right click. It uses Google's or DeepL's API (depending on which one you choose in settings), but doesn't keep your data.

## Extra stuff I did
* Modified about:config to allow custom search engines, set my default to SearX, and removed everything else. (specifically, the searx.pro instance)
* Since my CTRL key has been a bit funky lately, I edited my toolbar to have a screenshot button. This doesn't require an extension and can be done through the Customize Toolbar feature you can access with a right click.
* Disabled the ADs and Pocket on the Firefox front page because what the hell.
### AdNauseam configuration
AdNauseam is a fork of uBlock with an easier to access "strict block" feature. Strict block doesn't prevent you from viewing sites, it's advanced adblocking. These are the lists I have enabled from settings, rules, and some of the sites I strict-blocked:
#### Strict-blocked sites
```
annas-archive.org
bulbapedia.bulbagarden.net
facebook.com
knowyourmeme.com
libgen.li
mangareader.to
open.spotify.com
pastebin.com
www.animelyrics.com
www.cnn.com
www.instagram.com
www.opensubtitles.org
www.similarweb.com
www.thedailybeast.com
```
#### Filter lists (all available from AdNauseam settings) and rules
* Settings enabled: Auto-update filter lists, suspend network activity until all filter lists are loaded, parse and enforce cosmetic filters.
* Check "Ublock Filters"
* Enable EasyList under ADs section
* Enable EasyPrivacy from Privacy section
* Enable Online Malicious URL Blocklist from Malware Section
* Enable AdGuard Popup Overlays and Social Media filters from Annoyances section, and then Fanboy - Anti-Facebook and uBlock Filters - Annoyances.
* LocalCDN rules that pop up and are asked to be added to uBlock once the extension is installed.

## Other stuff
* I use the default dark Firefox theme.
* I utilize this bookmarklet to bypass Paywalls when all else fails (Unfortunately, guy who makes this site is not the greatest person in the world):
``javascript:void(location.href='https://1ft.io/proxy?q='+location.href);``
