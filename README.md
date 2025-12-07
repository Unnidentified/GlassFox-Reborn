# GlassFox-Reborn

A feature-rich fork of the original [GlassFox by Ashley-Cause](https://github.com/Ashley-Cause/GlassFox/). This theme brings full transparency to Firefox on macOS/Linux with added dynamic motion effects.

> **New in Reborn:**
> * **Dynamic Blur:** Inactive tabs are blurred to minimize distractions.
> * **Smart Hover:** Hovering over an inactive tab smoothly unblurs it.
> * **Kinetic Expansion:** Tabs expand with a smooth transition animation upon hover.

## Installation

### 1. Set up the Theme
1.  Open `about:profiles` in a new tab.
2.  Click **"Show in Finder"** (or Directory) under your current profile.
3.  Open the `chrome` folder (create one if it doesn't exist).
4.  Download `userChrome.css` and `userContent.css` from this repo and place them inside.

### 2. Activate Styling
1.  Go to `about:config` and click `Accept the Risk and Continue`.
2.  Set the following values to `true`:
    * `toolkit.legacyUserProfileCustomizations.stylesheets`
    * `widget.macos.titlebar-blend-mode.behind-window`
    * `browser.tabs.allow_transparent_browser` (if using userContent.css)

## Recommended Setup
To get the intended "Reborn" look:

1.  **[uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/)**
    * **Highly Recommended.** Blocks ads to keep the transparent UI clean and fast.
2.  **[Firefox Color](https://addons.mozilla.org/en-US/firefox/addon/firefox-color/)**
    * Install the extension.
    * Use this Unsplash photo: [View of Earth from an Airplane](https://unsplash.com/photos/a-view-of-the-earth-from-an-airplane-WfhF41ZM2dc).
    * Set it as your **Custom Background** in the extension settings.

## Configuration
Customize behavior via `about:config`:

| Feature | Name in `about:config` |
| :--- | :--- |
| Disable transparency | `glassfox.transparency.disabled` |
| Disable blur on inactive tabs | `glassfox.blur.disabled` |
| Disable expansion animation | `glassfox.animation.disabled` |
| Sidebar: Smaller tabs | `glassfox.sidebar.smaller-tabs` |
| Sidebar: Larger tabs | `glassfox.sidebar.larger-tabs` |

## Credits
Based on [GlassFox](https://github.com/Ashley-Cause/GlassFox/).
