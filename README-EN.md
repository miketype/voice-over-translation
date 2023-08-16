# Voice-over-translation

Русская версия: [Link](https://github.com/ilyhalight/voice-over-translation/blob/master/README.md)

The voice-over translation of the video is now available not only in YandexBrowser. Very grateful, **[Yandex.Translate](https://translate.yandex.ru/)** & **[sodapng](https://github.com/sodapng)** & **[mynovelhost](https://github.com/mynovelhost)** & **[SashaXser](https://github.com/SashaXser)**. Thanks <3

## Installing the extension:
1. Install the extension **[Tampermonkey](https://www.tampermonkey.net/)** (An alternative for Safari: **[UserScripts](https://apps.apple.com/app/userscripts/id1463298887 )**)
2. **[«Install the Script»](https://raw.githubusercontent.com/ilyhalight/voice-over-translation/master/dist/vot.user.js)** (**[Cloudflare version](https://raw.githubusercontent.com/ilyhalight/voice-over-translation/master/dist/vot-cloudflare.user.js)**)

### Useful links:
1. Version for VioletMonkey, FireMonkey, GreaseMonkey, AdGuard, UserScripts and some browsers: **[Link](https://raw.githubusercontent.com/ilyhalight/voice-over-translation/master/dist/vot-cloudflare.user.js)**
2. Terminal version: **[Link](https://github.com/ilyhalight/voice-over-translation/tree/master/vot-cli)**
3. Wiki: **[Link](https://github.com/ilyhalight/voice-over-translation/wiki)**

## List of supported sites:
You can see all the restrictions related to site support in [wiki](https://github.com/ilyhalight/voice-over-translation/wiki/%5BEN%5D-Supported-sites).
- **[YouTube](https://www.youtube.com)**
- **[Twitch](https://www.twitch.tv)**
- **[VK](https://vk.com)**
- **[Twitter](https://twitter.com/)**
- **[9GAG](https://9gag.com/gag/)**
- **[Rutube](https://rutube.ru/)**
- **[Bilibili](https://bilibili.com/)**
- **[Видео Mail.ru](https://my.mail.ru/video)**
- **[Vimeo](https://vimeo.com/)**
- **[XVideos](https://xvideos.com/)**
- **[PornHub](https://rt.pornhub.com/)**
- **[Bitchute](https://www.bitchute.com/)**
- **[[❌] Facebook*](https://facebook.com/)**
- **[[❌] TikTok](https://tiktok.com/)**
- **[Invidious](https://yewtu.be)**
- **[Piped](https://piped.video)**

## List of functionality:
1. Translation from one of the available languages into Russian. The language is detected automatically, if the language is not in the list or it was not possible to determine it, then a translation from English is used.
2. Translation from Russian into English
3. Automatic video translation when opening
4. Slider to change the video volume
5. Automatically set the video volume (as in Yandex browser)
6. [YouTube Only] Sync translation volume with video volume
7. [YouTube Only] Restrict translation of Russian-language videos

## How to build an extension?
1. Install NodeJS 18+
2. Install dependencies:
```bash
npm i
```
3. Building an extension:

   3.0. All versions at once:
   ```bash
   npm run build
   ```

   3.1. All minified versions at once:
   ```bash
   npm run build:min
   ```

   3.2. Only the regular version:
   ```bash
   npm run build:default
   ```

   3.3. Cloudflare version only:
   ```bash
   npm run build:cloudflare
   ```

   3.2. Only the usual min. versions:
   ```bash
   npm run build:default-min
   ```

   3.3. Only min. Cloudflare versions:
   ```bash
   npm run build:cloudflare-min
   ```

## Note:
1. I recommend allowing autoplay of "audio and video" to avoid errors when working with the extension
2. The extension cannot translate videos longer than 4 hours (translator API limitation)

## The extension has been tested in the following browsers:
| Status | Browser | Browser Version | Platform | Extension
|---|---|---|---|---
| ⠀✅ | Firefox Developer Edition | v106.0b4, 64 bit | Windows | Tampermonkey
| ⠀✅ | Firefox | v116.0.2 | Windows/Linux/Android | Tampermonkey
| ⠀✅ | LibreWolf | v100.0.2-1 | Windows | Tampermonkey
| ⠀✅ | Brave | v106.0.5249.91 | Windows | Tampermonkey
| ⠀✅ | MS Edge | v106.0.1370.34 | Windows, Linux | Tampermonkey
| ⠀✅ | Cent Browser | v4.3.9.248, 32 bit | Windows | Tampermonkey
| ⠀✅ | Cent Browser Beta | v5.0.1002.182, 64 bit | Windows | Tampermonkey
| ⠀✅ | Google Chrome | v106.0.5249.91 | Windows, MacOS, Linux | Tampermonkey, Violetmonkey
| ⠀✅ | Opera GX | LVL4 (core: 91.0.4516.36) | Windows | Tampermonkey
| ⠀✅ | Opera | v101.0.4843.43 | Windows, Linux | Tampermonkey
| ⠀✅ | Vivaldi | 5.7.2921.63 | Windows, Linux | Tampermonkey
| ⠀❔ | Safari | v15.6.1 | MacOS | Userscripts
| ⠀✅ | Kiwi Browser | v116.0.5845.61 | Android | Tampermonkey
| ⠀✅ | Firefox Nightly | v118.0a1 | Android | Tampermonkey

## Tested in the following extensions for user scripts:
| Status | Browser | Extension
|---|---|---
| ⠀✅ | Any | Tampermonkey
| ⠀[Download](https://raw.githubusercontent.com/ilyhalight/voice-over-translation/master/dist/vot-cloudflare.user.js) | Safari | Userscripts
| ⠀[Download](https://raw.githubusercontent.com/ilyhalight/voice-over-translation/master/dist/vot-cloudflare.user.js) | Any | Violetmonkey
| ⠀[Download](https://raw.githubusercontent.com/ilyhalight/voice-over-translation/master/dist/vot-cloudflare.user.js) | Any | [AdGuard Usercripts](https://kb.adguard.com/en/general/userscripts#supported-apps)
| ⠀[Download](https://raw.githubusercontent.com/ilyhalight/voice-over-translation/master/dist/vot-cloudflare.user.js) | Firefox | Firemonkey
| ⠀[Download](https://raw.githubusercontent.com/ilyhalight/voice-over-translation/master/dist/vot-cloudflare.user.js) | Any | Greasemonkey

![example btn](https://github.com/ilyhalight/voice-over-translation/blob/master/img/example_en.jpg "btn")

*: Banned on the territory of the Russian Federation
