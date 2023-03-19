<h1 align="center">
  <a href="https://bonjourr.fr"><img src="https://raw.githubusercontent.com/victrme/Bonjourr/master/src/assets/bonjourr.png" width="50%" alt="Bonjourr's website"></a>
</h1>

Bonjourr is a home page for your Internet browser inspired by the looks of iOS.<br>
While it aims to look and feel minimal, it still brings you lots of options to customise it to your liking. Here's some features:

-   🍏 iOS design language
-   🏞 Dynamic 4K backgrounds that change according to the mood of the day
-   ⚡️ Fast & lightweight!
-   🔎 Search bar (compatible with all search engines)
-   🕰 Analog clock with multiple clock faces
-   🌤 Weather
-   🔗 Quick Links
-   👋 Greets you by your name
-   🌘 Dark mode
-   🥖 Emoji as favicon
-   🧑‍💻 Custom CSS styling
-   📝 Custom fonts
-   🔒 Privacy focused
-   🌎 Multilanguage

<br>

## 🚀 Install Bonjourr!

<div>

[Chrome](https://chrome.google.com/webstore/detail/bonjourr-%C2%B7-minimalist-lig/dlnejlppicbjfcfcedcflplfjajinajd?hl=fr&authuser=0) •
[Firefox](https://addons.mozilla.org/fr/firefox/addon/bonjourr-startpage/) •
[Edge](https://microsoftedge.microsoft.com/addons/detail/bonjourr-%C2%B7-minimalist-l/dehmmlejmefjphdeoagelkpaoolicmid) •
[Safari](https://bonjourr.fr/use-bonjourr#-safari-desktop) •
[or try it online](https://online.bonjourr.fr)

</div>

<br>

## 👋 Get in touch

Check out [our Telegram group](https://t.me/BonjourrStartpage) where we discuss ideas, features and bug reports. You can also [send us an email](mailto:bonjourr.app@protonmail.com) or follow us [on Twitter](https://twitter.com/BonjourrTeam/) :)

<br>

## ✍️ Contribute

Here's a list of things you can do to help us out:

-   Give us feedback (positive and negative!) on how you use Bonjourr
-   Suggest new features or improvements of the existing ones
-   Create new [CSS snippets](https://bonjourr.fr/css-snippet) or [custom profiles](https://bonjourr.fr/profiles)
-   [Translate](https://bonjourr.fr/help#-translations) to a new language, or complete an existing one
-   Contribute to [our website](https://github.com/morceaudebois/bonjourr.fr)
-   Add new quotes (especially non english/french) to [the API](https://github.com/victrme/i18n-quotes)
-   Suggest new [Unsplash photos](https://bonjourr.fr/misc#-about-backgrounds)

<br>

## 🌟 Spread the word!

If you just want to say thank you and support our work, here's some ideas:

-   Tweet what you like about Bonjourr! (tag us, [@BonjourrTeam](https://twitter.com/BonjourrTeam/))
-   Leave a review on [Chrome](https://chrome.google.com/webstore/detail/bonjourr-%C2%B7-minimalist-lig/dlnejlppicbjfcfcedcflplfjajinajd?hl=fr&authuser=0), [Firefox](https://addons.mozilla.org/fr/firefox/addon/bonjourr-startpage/) or [Edge](https://microsoftedge.microsoft.com/addons/detail/bonjourr-%C2%B7-minimalist-l/dehmmlejmefjphdeoagelkpaoolicmid)
-   Add a GitHub Star to the repository ⭐️

<br>

## ☕ Donate

If you feel like we've earned it and you want to support independant open source developpers, we'll gladly accept your donations! It motivates us to keep improving Bonjourr and makes it feel more real :)

<div>

[Our Ko-Fi Page](https://ko-fi.com/bonjourr) •
[or donate in crypto](https://commerce.coinbase.com/checkout/095cc203-130d-4e56-9716-3aa10a202d9b)

</div>

<br>

## 👨‍💻 Running Bonjourr locally

### Chrome

#### Initialize

-   [Install npm](https://nodejs.org/en/download/)
-   `npm install -g pnpm`
-   `pnpm install`

#### Build

-   `pnpm run build`

#### Run & watch

-   `pnpm run chrome`

#### Browser extension launch

-   Go to `chrome://extensions`
-   Enable Developer mode
-   Load unpacked and select `/release/chrome` folder

### Firefox

-   Follow the initialize and build steps from Chrome

#### Run & watch

-   `pnpm run firefox`

#### Browser extension launch

-   Go to `about:debugging#/runtime/this-firefox`
-   Select "Load temporary Add-on"
-   Select `manifest.json` in `/release/firefox` folder

### Edge

-   Follow the initialize and build steps from Chrome

#### Run & watch

-   `pnpm run edge`

#### Browser extension launch

-   Go to `edge://extensions`
-   Enable Developer mode
-   Load unpacked and select `/release/edge` folder
-   Replace manifest with `/src/manifests/edge.json`
-   And rename `edge.json` to `manifest.json`

### Safari

-   Follow install steps on the [Safari repository](https://github.com/victrme/Bonjourr-Safari)

### Online

-   Follow the initialize and build steps from Chrome

#### Run & watch

-   `pnpm run online`

#### Web server launch

-   Open a live server from `/release/online` folder

<br>

## 🔧 Built with

-   Styled with [Sass](https://sass-lang.com/guide)
-   Scripts with pure JS
-   Releases bundled with Gulp, [see dependencies](https://github.com/victrme/Bonjourr/network/dependencies)
-   Our tiny hands 🙌

<br>

## 👀 Authors

-   **Tahoe Beetschen** · [portfolio](https://tahoe.be) · [GitHub](https://github.com/Tahoooe)
-   **Victor Azevedo** · [portfolio](https://victr.me) · [GitHub](https://github.com/victrme)

<br>

## 🧑‍💻 Contributors and translations

-   **🇸🇪 Swedish translation** · [Benjamin Horn](https://benjaminhorn.io/) · [GitHub](https://github.com/beije)
-   **🇳🇱 Dutch translation** · [Osman Temiz](https://www.reddit.com/user/manllac)
-   **🇵🇱 Polish translation** · [Mateusz K](https://www.reddit.com/user/DiVine92) & [Jakub Mikuło](https://github.com/jmikulo)
-   **🇷🇺 Russian translation** · [OemDef](https://www.reddit.com/user/OemDef)
-   **🇨🇳 Simplified Chinese translation** · Shuhuai Cao · [GitHub](https://github.com/csh980717)
-   **🇧🇷 Brazilian Portuguese translation** · [Adilson Santos](http://adilsonsantos.netlify.com) · [Github](https://github.com/adilsonfsantos)
-   **🇸🇰 Slovak translation** · Roman Bartík
-   **🇩🇪 German translation** · [Bernhard Wittmann](https://bernhardwittmann.com/) · [GitHub](https://github.com/berniwittmann)
-   **🇮🇹 Italian translation** · Trazalca · [GitHub](https://github.com/Trazalca)
-   **🇪🇸 Spanish translation** · José Alberto · [GitHub](https://github.com/joatb)
-   **🇺🇦 Ukrainian translation** · [Anton Boksha](https://antonboksha.dev/) · [GitHub](https://github.com/4doge)
-   **🇹🇷 Turkish translation** · Müslüm Barış Korkmazer · [GitHub](https://github.com/babico)
-   **🇮🇩 Indonesian translation** · Imam Ali Mustofa · [GitHub](https://github.com/darkterminal)
-   **🇩🇰 Danish translation** · kar1 · [GitHub](https://github.com/kar1)
-   **🇫🇮 Finnish translation** · jaajko · [Jaajko](https://jaajko.fi) · [GitHub](https://github.com/jaajko)
-   **🇭🇺 Hungarian translation** · cook3r · [GitHub](https://github.com/cook3r)
-   **🇭🇰 Traditional Chinese translation** · Pu · [GitHub](https://github.com/unknownnumbers)
