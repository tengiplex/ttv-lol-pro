<h1 align="center">
  <img src="src/images/brand/icon.png" height="100" width="100" alt="Icon" />
  <br />
  TTV LOL PRO
  <br />
</h1>

<div align="center">
  <a href="https://github.com/younesaassila/ttv-lol-pro/issues">
    <img
      alt="GitHub issues"
      src="https://img.shields.io/github/issues/younesaassila/ttv-lol-pro"
    />
  </a>
  <a href="https://github.com/younesaassila/ttv-lol-pro/stargazers">
    <img
      alt="GitHub stars"
      src="https://img.shields.io/github/stars/younesaassila/ttv-lol-pro"
    />
  </a>
  <a href="https://github.com/younesaassila/ttv-lol-pro/releases">
    <img
      alt="GitHub all releases"
      src="https://img.shields.io/github/downloads/younesaassila/ttv-lol-pro/total"
    />
  </a>
</div>

<br />

TTV LOL PRO removes most livestream ads from Twitch. This is free, don't expect it to be perfect. Issues? Complain to Twitch

This fork:

- removes livestream ads from Twitch,
- lets you whitelist channels (Firefox only),
- improves TTV LOL's popup by showing stream status and "Whitelist" button (Firefox only),
- lets you add custom primary/fallback proxies.

**Recommendations:**

- [uBlock Origin](https://ublockorigin.com/)

  - removes banner ads,
  - removes ads on VODs.

## Screenshot

<div align="center">
  <img
    src="https://github.com/younesaassila/ttv-lol-pro/assets/47226184/9841764f-a9ae-46da-9236-e1cce0164081"
    alt="Popup on Firefox"
    height="450"
  />
</div>

## Installation

> ⚠️ **Please remove any other Twitch-specific ad blocker (this includes the [VAFT](https://github.com/pixeltris/TwitchAdSolutions#scripts) script). [uBlock Origin](https://ublockorigin.com/) is recommended as it is a general-purpose ad blocker. Please clear your browser's cache after installing the beta.**

1. Download the version for your browser under the "Assets" section of the [latest release](https://github.com/younesaassila/ttv-lol-pro/releases).

- **Chrome _(Permanent)_:** Unzip > Go to `chrome://extensions` > Enable developer mode > Load unpacked
- **Firefox all editions _(Temporary)_:** Go to `about:debugging#/runtime/this-firefox` > Load Temporary Add-on
- **[Firefox Developer Edition](https://www.mozilla.org/en-US/firefox/developer/) _(Permanent)_:** Go to `about:config` > Set `xpinstall.signatures.required` to `false` > Extensions page > Gear > Install Add-on From File

## Credits

- Extension maintained by [Younes Aassila](https://github.com/younesaassila)
- Default proxies maintained by [zGato](https://github.com/zGato)
