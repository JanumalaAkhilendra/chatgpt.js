<div id="repo-cover" align="center">

<div align="center">
    <h6>
        <a href="https://github.com/KudoAI/chatgpt.js/tree/main/docs">
            <picture>
                <source type="image/svg+xml" media="(prefers-color-scheme: dark)" srcset="https://media.chatgptjs.org/images/icons/earth-americas-white-padded-icon17x15.svg?714b6a1">
                <img src="https://media.chatgptjs.org/images/icons/earth-americas-padded-icon17x15.svg?714b6a1">
            </picture>
        </a>
        English |
        <a href="https://github.com/KudoAI/chatgpt.js/tree/main/docs/zh-cn#readme">简体中文</a> |
        <a href="zh-tw#readme">繁體中文</a> |
        <a href="https://github.com/KudoAI/chatgpt.js/tree/main/docs/ja#readme">日本</a> |
        <a href="https://github.com/KudoAI/chatgpt.js/tree/main/docs/ko#readme">한국인</a> |
        <a href="https://github.com/KudoAI/chatgpt.js/tree/main/docs/hi#readme">हिंदी</a> |
        <a href="https://github.com/KudoAI/chatgpt.js/tree/main/docs/np#readme">नेपाली</a> |
        <a href="https://github.com/KudoAI/chatgpt.js/tree/main/docs/de#readme">Deutsch</a> |
        <a href="https://github.com/KudoAI/chatgpt.js/tree/main/docs/es#readme">Español</a> |
        <a href="https://github.com/KudoAI/chatgpt.js/tree/main/docs/fr#readme">Français</a> |
        <a href="https://github.com/KudoAI/chatgpt.js/tree/main/docs/it#readme">Italiano</a> |
        <a href="https://github.com/KudoAI/chatgpt.js/tree/main/docs/nl#readme">Nederlands</a> |
        <a href="https://github.com/KudoAI/chatgpt.js/tree/main/docs/pt#readme">Português</a> |
        <a href="https://github.com/KudoAI/chatgpt.js/tree/main/docs/vi#readme">Việt</a>
    </h6>
</div>

<br>

<a href="https://chatgpt.js.org">
    <picture>
        <source type="image/png" media="(prefers-color-scheme: dark)" srcset="https://media.chatgptjs.org/images/logos/chatgpt.js/with-reflection/darkmode.png?bc68d0c">
        <img width=800 src="https://media.chatgptjs.org/images/logos/chatgpt.js/with-reflection/lightmode.png?bc68d0c">
    </picture>
</a>

### 🤖 A powerful client-side JavaScript library for ChatGPT

</div>

<br>

<div id="shields" align="center">

[![](https://img.shields.io/github/stars/KudoAI/chatgpt.js?label=Stars&color=af68ff&logo=github&logoColor=white&labelColor=464646&style=for-the-badge)](https://github.com/KudoAI/chatgpt.js/stargazers)
[![](https://img.shields.io/badge/License-MIT-green.svg?logo=internetarchive&logoColor=white&labelColor=464646&style=for-the-badge)](https://github.com/KudoAI/chatgpt.js/blob/main/LICENSE.md)
[![](https://img.shields.io/github/commit-activity/m/KudoAI/chatgpt.js?label=Commits&logo=github&logoColor=white&labelColor=464646&style=for-the-badge)](https://github.com/KudoAI/chatgpt.js/commits/main)
[![](https://img.shields.io/github/size/KudoAI/chatgpt.js/dist/chatgpt.min.js?branch=v2.9.2&label=Minified%20Size&logo=databricks&logoColor=white&labelColor=464646&color=ff69b4&style=for-the-badge)](https://github.com/KudoAI/chatgpt.js/tree/v2.9.2/dist/chatgpt.min.js)
[![](https://img.shields.io/codefactor/grade/github/kudoai/chatgpt.js?label=Code+Quality&logo=codefactor&logoColor=white&labelColor=464646&color=1acc6c&style=for-the-badge)](https://www.codefactor.io/repository/github/kudoai/chatgpt.js)
[![](https://img.shields.io/badge/dynamic/json?url=https%3A%2F%2Fsonarcloud.io%2Fapi%2Fmeasures%2Fcomponent%3Fcomponent%3Dkudoai_chatgpt.js%26metricKeys%3Dvulnerabilities&query=%24.component.measures.0.value&style=for-the-badge&logo=sonarcloud&logoColor=white&labelColor=464646&label=Vulnerabilities&color=gold)](https://sonarcloud.io/component_measures?metric=new_vulnerabilities&id=kudoai_chatgpt.js)
[![](https://img.shields.io/badge/Mentioned_in-Awesome-cca8c4?logo=awesomelists&logoColor=white&labelColor=464646&style=for-the-badge)](https://github.com/sindresorhus/awesome-chatgpt#javascript)
[![](https://img.shields.io/badge/Featured_on-Product_Hunt-ff6154?logo=producthunt&logoColor=white&labelColor=464646&style=for-the-badge)](https://www.producthunt.com/posts/chatgpt-js)
![](https://img.shields.io/badge/jsDelivr_Requests-1,500,000+-2bbbd8.svg?logo=jsdelivr&logoColor=white&labelColor=464646&style=for-the-badge)

</div>

<img height=8px width="100%" src="https://media.chatgptjs.org/images/separators/gradient-aqua.png?78210a7">

<div id="intro">

## 💡 About

</div>

<span style="color: white">chatgpt.js</span> is a <span style="color: white">powerful</span> JavaScript library that allows for <span style="color: white">super easy</span> interaction w/ the ChatGPT DOM.

- Feature-rich
- Object-oriented
- Easy-to-use
- Lightweight (yet optimally performant)

<img height=8px width="100%" src="https://media.chatgptjs.org/images/separators/gradient-aqua.png?78210a7">

<div id="importing">

## ⚡ Importing the library

</div>

> **Note** _To always import the latest version (not recommended in production!) replace the versioned jsDelivr URL with: `https://cdn.jsdelivr.net/npm/@kudoai/chatgpt.js/chatgpt.min.js`_

### ES6:

```js
(async () => {
    await import('https://cdn.jsdelivr.net/npm/@kudoai/chatgpt.js@2.9.2/dist/chatgpt.min.js');
    // Your code here...
})();
```

### ES5:

```js
var xhr = new XMLHttpRequest();
xhr.open('GET', 'https://cdn.jsdelivr.net/npm/@kudoai/chatgpt.js@2.9.2/dist/chatgpt.min.js');
xhr.onload = function () {
    if (xhr.status === 200) {
        var chatgptJS = document.createElement('script');
        chatgptJS.textContent = xhr.responseText;
        document.head.append(chatgptJS);
        yourCode(); // runs your code
    }
};
xhr.send();

function yourCode() {
    // Your code here...
}
```

### <img style="margin: 0 2px -0.065rem 0" height=17 src="https://cdn.jsdelivr.net/gh/KudoAI/chatgpt.js@e26f2cf/starters/media/images/icons/tampermonkey-icon28.png"><img style="margin: 0 2px -0.035rem 1px" height=17.5 src="https://cdn.jsdelivr.net/gh/KudoAI/chatgpt.js@0c37090/starters/media/images/icons/violentmonkey-icon100.png"> Greasemonkey:

> **Note** _To use a starter template: [kudoai/chatgpt.js-greasemonkey-starter](https://github.com/KudoAI/chatgpt.js-greasemonkey-starter)_

```js
...
// @require https://cdn.jsdelivr.net/npm/@kudoai/chatgpt.js@2.9.2/dist/chatgpt.min.js
// ==/UserScript==

// Your code here...
```

### <img style="margin: 0 2px -1px 0" height=16 src="https://www.google.com/chrome/static/images/favicons/apple-icon-60x60.png"> Chrome:

> **Note** _To use a starter template: [kudoai/chatgpt.js-chrome-starter](https://github.com/KudoAI/chatgpt.js-chrome-starter)_

Since Google does not allow remote code, importing chatgpt.js locally is required:

1. Save https://raw.githubusercontent.com/KudoAI/chatgpt.js/main/chatgpt.js to a subdirectory (`lib` in this example)

2. Add ES6 export statement to end of `lib/chatgpt.js`
```js
...
export { chatgpt }
```

3. In project's (V3) `manifest.json`, add `lib/chatgpt.js` as a web accessible resource
```json
    "web_accessible_resources": [{
        "matches": ["<all_urls>"],
        "resources": ["lib/chatgpt.js"]
    }],
```

4. In scripts that need `chatgpt.js` (foreground/background alike), import it like so:
```js
(async () => {
    const { chatgpt } = await import(chrome.runtime.getURL('lib/chatgpt.js'));
    // Your code here...
})();
```

<img height=8px width="100%" src="https://media.chatgptjs.org/images/separators/gradient-aqua.png?78210a7">

<div id="npm">

## 💾 Downloading via npm:

</div>

To download **chatgpt.js** for local customization, run the following command in your project's root:

```bash
npm install @kudoai/chatgpt.js
```

After installation, navigate to `node_modules/@kudoai/chatgpt.js` to find the library source.

</div>

<img height=8px width="100%" src="https://media.chatgptjs.org/images/separators/gradient-aqua.png?78210a7">

<div id="usage">

## 💻 Usage

</div>

**chatgpt.js** was written w/ ultra flexibility in mind.

For example:

```js
chatgpt.getLastResponse();
chatgpt.getLastReply();
chatgpt.response.getLast();
chatgpt.get('reply', 'last');
```

Each call equally fetches the last response. If you think it works, it probably will... so just type it!

If it didn't, check out the extended [userguide](https://github.com/KudoAI/chatgpt.js/blob/v2.9.2/docs/USERGUIDE.md), or simply submit an [issue](https://github.com/KudoAI/chatgpt.js/issues) or [PR](https://github.com/KudoAI/chatgpt.js/pulls) and it will be integrated, ezpz!

<img height=8px width="100%" src="https://media.chatgptjs.org/images/separators/gradient-aqua.png?78210a7">

<div id="showcase">

## 🤖 Made with chatgpt.js

</div>

https://github.com/KudoAI/chatgpt.js/assets/10906554/f53c740f-d5e0-49b6-ae02-3b3140b0f8a4

#

### <picture><source media="(prefers-color-scheme: dark)" srcset="https://i.imgur.com/RduASbD.png"><img width=16 src="https://raw.githubusercontent.com/adamlui/chatgpt-addons/main/media/icons/openai-favicon64.png"></picture> [Autoclear ChatGPT History](https://autoclearchatgpt.com) &nbsp;<a href="https://github.com/awesome-scripts/awesome-userscripts#chatgpt" target="_blank" rel="noopener"><img src="https://awesome.re/mentioned-badge.svg" style="margin:0 0 -2px 5px"></a>

> Auto-clear your ChatGPT query history for maximum privacy.
<br>[Install](https://docs.autoclearchatgpt.com/#-installation) /
[Readme](https://docs.autoclearchatgpt.com/#readme) /
[Discuss](https://github.autoclearchatgpt.com/discussions)

### <img src="https://media.bravegpt.com/images/icons/bravegpt/icon48.png" width=18> [BraveGPT](https://bravegpt.com) &nbsp;<a href="https://www.producthunt.com/posts/bravegpt?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-bravegpt" target="_blank" rel="noopener"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=385630&theme=light" style="width: 112px; height: 24px; margin:0 0 -4px 5px;" width="112" height="24" /></a>

> Display ChatGPT answers in Brave Search sidebar (powered by GPT-4!)
<br>[Install](https://docs.bravegpt.com/#-installation) /
[Readme](https://docs.bravegpt.com/#readme) /
[Discuss](https://github.bravegpt.com/discussions)

### <picture><source media="(prefers-color-scheme: dark)" srcset="https://i.imgur.com/RduASbD.png"><img width=16 src="https://raw.githubusercontent.com/adamlui/chatgpt-userscripts/main/media/icons/openai-favicon64.png"></picture> [ChatGPT Auto-Continue ⏩](https://chatgptautocontinue.com) &nbsp;<a href="https://github.com/awesome-scripts/awesome-userscripts#chatgpt" target="_blank" rel="noopener"><img src="https://awesome.re/mentioned-badge.svg" style="margin:0 0 -3px 3px"></a>

> Automatically continue generating multiple ChatGPT responses.
<br>[Install](https://docs.chatgptautocontinue.com/#-installation) /
[Readme](https://docs.chatgptautocontinue.com/#readme) /
[Discuss](https://github.chatgptautocontinue.com/discussions)

### <picture><source media="(prefers-color-scheme: dark)" srcset="https://i.imgur.com/RduASbD.png"><img width=16 src="https://raw.githubusercontent.com/adamlui/chatgpt-addons/main/media/icons/openai-favicon64.png"></picture> [ChatGPT Auto Refresh ↻](https://chatgptautorefresh.com) &nbsp;<a href="https://github.com/awesome-scripts/awesome-userscripts#chatgpt" target="_blank" rel="noopener"><img src="https://awesome.re/mentioned-badge.svg" style="margin:0 0 -2px 5px"></a>

> Keeps ChatGPT sessions fresh to eliminate network errors + Cloudflare checks.
<br>[Install](https://docs.chatgptautorefresh.com/#-installation) /
[Readme](https://docs.chatgptautorefresh.com/#readme) /
[Discuss](https://github.chatgptautorefresh.com/discussions)

### <img src="https://media.ddgpt.com/images/icons/duckduckgpt/icon48.png" width=17> [DuckDuckGPT](https://duckduckgpt.com) &nbsp;<a href="https://www.producthunt.com/posts/duckduckgpt?utm_source=badge-featured&utm_medium=badge&utm_souce=badge-duckduckgpt" target="_blank" rel="noopener"><img src="https://api.producthunt.com/widgets/embed-image/v1/featured.svg?post_id=379261&theme=light" style="width: 112px; height: 24px; margin:0 0 -4px 5px;" width="112" height="24" /></a>

> Display ChatGPT answers in DuckDuckGo sidebar (powered by GPT-4!)
<br>[Install](https://docs.ddgpt.com/#-installation) /
[Readme](https://docs.ddgpt.com/#readme) /
[Discuss](https://github.ddgpt.com/discussions)

### <picture><source media="(prefers-color-scheme: dark)" srcset="https://media.googlegpt.io/images/icons/googlegpt/white/icon32.png"><img width=17 src="https://media.googlegpt.io/images/icons/googlegpt/black/icon32.png"></picture> [GoogleGPT](https://googlegpt.io) &nbsp;<a href="https://github.com/awesome-scripts/awesome-userscripts#chatgpt" target="_blank" rel="noopener"><img src="https://media.googlegpt.io/images/badges/awesome/badge.svg" style="margin:0 0 -2px 5px"></a>

> Display ChatGPT answers in Google Search sidebar (powered by GPT-4!)
<br>[Install](https://greasyfork.org/scripts/478597-googlegpt) /
[Readme](https://docs.googlegpt.io/#readme) /
[Discuss](https://github.googlegpt.io/discussions)

### <picture><img src="https://raw.githubusercontent.com/micz/micz.github.io/master/static/images/thunderbird-64px.png" width="24" height="24"></picture> [ThunderAI](https://micz.it/thunderdbird-addon-thunderai/) 

> Use ChatGPT in Thunderbird to enhance you emails, even with a free account! 
<br>[Install](https://addons.thunderbird.net/it/thunderbird/addon/thunderai/) /
[Readme](https://micz.it/thunderdbird-addon-thunderai/) /
[Support](https://github.com/micz/ThunderAI/issues)

<p><br>

<a href="https://chatgptinfinity.com" target="_blank" rel="noopener">
    <img width=555 src="https://raw.githubusercontent.com/adamlui/chatgpt-infinity/main/chrome/media/images/tiles/marquee-promo-tile-1400x560.png">
</a>

<p><br>

<a href="https://chatgptwidescreen.com" target="_blank" rel="noopener">
    <img width=555 src="https://raw.githubusercontent.com/adamlui/chatgpt-widescreen/main/chrome/media/images/tiles/marquee-promo-tile-1400x560.png">
</a>

<p><br>

<p id="showcase-cta">
If you've made something w/ chatgpt.js you want to share, email <a href="mailto:showcase@chatgptjs.org">showcase@chatgptjs.org</a> or just open a <a href="https://github.com/KudoAI/chatgpt.js/pulls" target="_blank" rel="noopener">pull request</a>!
</p>

<img height=8px width="100%" src="https://media.chatgptjs.org/images/separators/gradient-aqua.png?78210a7">

<div id="contributors">

## 🧠 Contributors

</div>

This library exists thanks to code, translations, issues & ideas from the following contributors:

<div align="center"><br>

[![](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/10906554?first-contrib=2023.03.15&h=51&w=51&mask=circle&maxage=7d "@adamlui")](https://github.com/adamlui)
[![](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/71683364?first-contrib=2023.03.16-get-functions&h=51&w=51&mask=circle&maxage=7d "@mefengl")](https://github.com/mefengl)
[![](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/131989355?first-contrib=2023.04.30-doc-translations&h=51&w=51&mask=circle&maxage=7d "@Zin6969")](https://github.com/Zin6969)
[![](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/30551844?first-contrib=2023.05.02-getlastresponse-bug-report&h=51&w=51&mask=circle&maxage=7d "@madruga8")](https://github.com/madruga8)
[![](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/54934866?first-contrib=2023.05.01-clearchats-discard-fix&h=51&w=51&mask=circle&maxage=7d "@XiaoYingYo")](https://github.com/XiaoYingYo)
[![](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/129722778?first-contrib=2023.05.24-css-readability&h=51&w=51&mask=circle&maxage=7d "@AliAlSarre")](https://github.com/AliAlSarre)
[![](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/100418457?first-contrib=2023.06.02-send-function-bug-report&h=51&w=51&mask=circle&maxage=7d "@madkarmaa")](https://github.com/madkarmaa)
[![](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/1170326?first-contrib=2023.06.10-html-parser-idea&h=51&w=51&mask=circle&maxage=7d "@wamoyo")](https://github.com/wamoyo)
[![](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/33952?first-contrib=2023.06.10-html-parser-idea&h=51&w=51&mask=circle&maxage=7d "@meiraleal")](https://github.com/meiraleal)
[![](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/22633385?first-contrib=2023.07.11-fix-ja-doc-md&h=51&w=51&mask=circle&maxage=7d "@eltociear")](https://github.com/eltociear)
[![](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/72805486?first-contrib=2023.07.14-enhance-ko-docs&h=51&w=51&mask=circle&maxage=7d "@Rojojun")](https://github.com/Rojojun)
[![](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/62183023?first-contrib=2023.07.24-fix-hi-doc&h=51&w=51&mask=circle&maxage=7d "@iamnishantgaharwar")](https://github.com/iamnishantgaharwar)
[![](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/629429?first-contrib=2023.07.31-homepage-starry-bg&h=51&w=51&mask=circle&maxage=7d "@hakimel")](https://github.com/hakimel)
[![](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/73983677?first-contrib=2023.08.23-fix-readme-typos&h=51&w=51&mask=circle&maxage=7d "@omahs")](https://github.com/omahs)
[![](https://images.weserv.nl/?url=https://i.imgur.com/DQVC7vj.jpg?first-contrib=2023.09.19-add-dmarc-policy&h=51&w=51&mask=circle&maxage=7d "Najam Ul Arfeen")](https://www.linkedin.com/in/najam-ul-arfeen-khan/)
[![](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/110587589?first-contrib=2023.10.13-translate-docs-to-nepali&h=51&w=51&mask=circle&maxage=7d "@iambijayd")](https://github.com/iambijayd)
[![](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/4698976?first-contrib=2023.10.29-remove-outdated-mv2-preface-from-docs&h=51&w=51&mask=circle&maxage=7d "@abhinavm24")](https://github.com/abhinavm24)
[![](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/77867745?first-contrib=2023.11.4-getchatdetails-bug-report&h=51&w=51&mask=circle&maxage=7d "@deyvisml")](https://github.com/deyvisml)
[![](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/150537240?first-contrib=2023.11.15-regenerate-btn-changed-bug-email&h=51&w=51&mask=circle&maxage=7d "@philly88r")](https://github.com/philly88r)
[![](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/9730392?first-contrib=2023.12.18-get-response-from-dom-request&h=51&w=51&mask=circle&maxage=7d "@thomasgauthier")](https://github.com/thomasgauthier)
[![](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/42911524?first-contrib=2024.1.17-add-custom-gpt-support&h=51&w=51&mask=circle&maxage=7d "@pranav-bhatt")](https://github.com/pranav-bhatt)
[![](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/13976824?first-contrib=2024.01.31-aria-labels-unreliable-bug-report&h=50&w=50&mask=circle&maxage=7d "@hopana")](https://github.com/hopana)
[![](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/26219737?first-contrib=2024.2.2-data-key-message-bug-fix&h=50&w=50&mask=circle&maxage=7d "@emtry")](https://github.com/emtry)
[![](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/44357327?first-contrib=2024.2.14-msg-fetching-for-localization-fails-report&h=51&w=51&mask=circle&maxage=7d "@thedayofcondor")](https://github.com/thedayofcondor)
[![](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/111466842?first-contrib=2024.2.15-add-en-gb-locale&h=51&w=51&mask=circle&maxage=7d "@Luwa-Tech")](https://github.com/Luwa-Tech)
[![](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/61795?first-contrib=2024.5.9-update-css-selector-for-getregeneratebutton&h=51&w=51&mask=circle&maxage=7d "@micz")](https://github.com/micz)
[![](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/17583722?first-contrib=2024.5.17-chrome-starter-manifest-matches-outdated-alert&h=51&w=51&mask=circle&maxage=7d "@imranaalam")](https://github.com/imranaalam)
[![](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/in/29110&h=51&w=51&mask=circle&maxage=7d "Dependabot")](https://github.com/dependabot)
<a href="https://chatgpt.com"><picture><source media="(prefers-color-scheme: dark)" srcset="https://images.weserv.nl/?url=https://cdn.jsdelivr.net/gh/KudoAI/chatgpt.js@main/media/images/icons/platforms/chatgpt/black-on-white/icon189.png?h=50&w=50&mask=circle&maxage=7d"><img src="https://images.weserv.nl/?url=https://cdn.jsdelivr.net/gh/KudoAI/chatgpt.js@main/media/images/icons/platforms/chatgpt/white-on-black/icon189.png?h=50&w=50&mask=circle&maxage=7d" title="ChatGPT"></picture></a>
<a href="https://poe.com"><picture><source media="(prefers-color-scheme: dark)" srcset="https://images.weserv.nl/?url=https://cdn.jsdelivr.net/gh/KudoAI/chatgpt.js@main/media/images/icons/platforms/poe/w-purple-blue-stripes/black-on-white/icon175.png?h=50&w=50&mask=circle&maxage=7d"><img src="https://images.weserv.nl/?url=https://cdn.jsdelivr.net/gh/KudoAI/chatgpt.js@main/media/images/icons/platforms/poe/w-purple-blue-stripes/white-on-black/icon175.png?h=50&w=50&mask=circle&maxage=7d" title="Poe"></picture></a>
[![](https://images.weserv.nl/?url=https://avatars.githubusercontent.com/u/31427850?h=51&w=51&mask=circle&maxage=7d "@ImgBotApp")](https://github.com/ImgBotApp)

</div><br>

<img height=8px width="100%" src="https://media.chatgptjs.org/images/separators/gradient-aqua.png?78210a7">

<div id="partners">

## 🤝 Partners

</div>

**chatgpt.js** is funded in part by:

<div id="partners-collage" align="center">

<picture>
    <source type="image/png" media="(prefers-color-scheme: dark)" srcset="https://media.chatgptjs.org/images/logos/partners/collage/white.png?3109608">
    <img width=888 src="https://media.chatgptjs.org/images/logos/partners/collage/black.png?3109608">
</picture>

</div>

<br>

<img height=8px width="100%" src="https://media.chatgptjs.org/images/separators/gradient-aqua.png?78210a7">

<div align="center">

**[Releases](https://github.com/KudoAI/chatgpt.js/releases)** /
[Userguide](https://github.com/KudoAI/chatgpt.js/blob/v2.9.2/docs/USERGUIDE.md) /
[Discuss](https://github.com/KudoAI/chatgpt.js/discussions) /
<a href="#--------------------------------------------------------------------------------english---------简体中文---------繁體中文---------日本---------한국인---------हिंदी---------नेपाली---------deutsch---------español---------français---------italiano---------nederlands---------português---------việt----">Back to top ↑</a>

</div>
