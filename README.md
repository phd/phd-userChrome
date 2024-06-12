phd-userChrome
=================================

A set of userChrome.css styles for Firefox UI:

- `phd-userChrome-active-tab-accent-background.css`
- `phd-userChrome-auto-hide-navigation-and-bookmarks.css` (experimental)
- `phd-userChrome-bookmarks-styling.css`
- `phd-userChrome-disable-proton-ui.css`
- `phd-userChrome-findbar-styling.css`
- `phd-userChrome-floating-menubar.css`
- `phd-userChrome-floating-notifications.css`
- `phd-userChrome-kde-breeze-icons.css`
- `phd-userChrome-menu-items-styling.css`
- `phd-userChrome-multiline-bookmarks.css`
- `phd-userChrome-places-window-horizontal-layout.css`
- `phd-userChrome-remove-megabar.css`
- `phd-userChrome-smaller-items-in-extensions-panel.css`
- `phd-userChrome-tabs-styling.css`
- `phd-userChrome-toolbars-order-and-styling.css`

`ALL.css` includes all non-experimental styles.

Installation
------------

`cd ~/.mozilla/firefox/*.default-release/`

`mkdir -p chrome`

`cd chrome`

`git clone https://github.com/phd/phd-userChrome`

`echo '@import "phd-userChrome/ALL.css";' >> userChrome.css`

Navigate to `about:config` and set `toolkit.legacyUserProfileCustomizations.stylesheets` to `true`.

You may also want to set:

- `browser.compactmode.show` to `true` and `browser.uidensity` to `1`
- `browser.tabs.inTitlebar` to `0`
- `browser.toolbars.bookmarks.visibility` to `always`

Restart Firefox browser.

Updating
--------

`cd ~/.mozilla/firefox/*.default-release/chrome/phd-userChrome/`

`git pull`

Restart Firefox browser.
