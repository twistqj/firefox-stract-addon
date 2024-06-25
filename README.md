# Stract addon for Firefox

Adds the [Stract search engine](https://stract.com/) to your firefox browser. In the URL bar you simply type

`@stract search_query`

This addon also enables you to set Stract as your default search engine, but it does not happen automatically.

There is currently no support for [optics](https://stract.com/settings/optics) or similar things.

This project is based on [firefox-yt-addon](https://github.com/atahabaki/firefox-yt-addon) by [atahabaki](https://github.com/atahabaki). I liked to have something similar for Stract also so this is why I created this fork.

## Screenshots

![@stract in search bar](./show.png)

## How does this work?

Firefox has `chrome_settings_overrides.search_provider` to add your search engine to the omnibox. To learn more, take a look at [MDN docs](https://developer.mozilla.org/en-US/docs/Mozilla/Add-ons/WebExtensions/manifest.json/chrome_settings_overrides).
