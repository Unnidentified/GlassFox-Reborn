# GlassFox-Reborn

A feature-rich fork of the original [GlassFox by Ashley-Cause](https://github.com/Ashley-Cause/GlassFox/). This theme brings full transparency to Firefox on macOS/Linux with added dynamic motion effects.
![CleanShot 2025-12-07 at 04 26 36@2x](https://github.com/user-attachments/assets/67ea520a-e207-4303-a85c-939832af4db1)
![collapsed](https://github.com/user-attachments/assets/efe0b527-48e9-430a-876f-3a93a0f55c53)
![expanded](https://github.com/user-attachments/assets/7dda6730-b99d-4b74-ae5e-669c88f064fb)
![horizontal](https://github.com/user-attachments/assets/dbc8e91e-aa4f-4edb-aad8-900b91e235df)


> **New in Reborn:**
> * **Dynamic Blur:** Inactive tabs are blurred to minimize distractions.
> * **Smart Hover:** Hovering over an inactive tab smoothly unblurs it.
> * **Kinetic Expansion:** Tab text expand with a smooth transition animation upon hover.

## Installation

### 1. Set up the Theme
1.  Open `about:profiles` in a new tab.
2.  Click **"Show in Finder"** (or Directory) under your current profile.
3.  Download the `chrome` folder from this repo and place them inside.
4.  Relaunch Firefox.

### 2. Activate Styling
1.  Go to `about:config` and click `Accept the Risk and Continue`.
2.  Set the following values to `true`:
    * `toolkit.legacyUserProfileCustomizations.stylesheets`
    * `widget.macos.titlebar-blend-mode.behind-window`
    * `browser.tabs.allow_transparent_browser` (if using userContent.css)

## Mandatory/highly-recommended for a better web-experience.

1.  **[uBlock Origin](https://addons.mozilla.org/en-US/firefox/addon/ublock-origin/)**
    * **Highly Recommended.** Full fledged open-source ad-blocker.
2.  **['Improve YouTube'](https://addons.mozilla.org/en-US/firefox/addon/youtube-addon/)**
3.  * Install it. You won't regret it.
4.  **[Return Youtube Dislike](https://addons.mozilla.org/en-US/firefox/addon/return-youtube-dislikes/)**
5.  **[Ultima Dark](https://addons.mozilla.org/en-US/firefox/addon/ultimadark/)**
6.  * **Fastest dark mode** for firefox equiparable with chromium flags.
7.  **[Yet Another Smooth Scrolling WE](https://addons.mozilla.org/en-US/firefox/addon/yass-we/?utm_source=addons.mozilla.org&utm_medium=referral&utm_content=search)**
8.  **[Minim New Start Page](https://addons.mozilla.org/en-US/firefox/addon/minim-minimalist-new-tab/)**
9.  **[Firefox Color](https://addons.mozilla.org/en-US/firefox/addon/firefox-color/)**
    * Install the extension.
    * Click on this theme and apply colour theme: [Firefox Brown](https://color.firefox.com/?theme=XQAAAAIxAgAAAAAAAABBqYhm849SCicxcUBMsXcGHf3p79EhVPrI8K8LqY6dyVywP5j0c4QSlcOzgjprK_GGRyoiJXg5SbkUvSCorNAwbsfE62mfpKioe9QwseWZAO7sz9SnXvMNHRAP7n08wQcejsL19UHFQFlxslAv0J3gLHHC0OYO_i4QTE9ig7UzMVsOB_ad7A68eGHzl38qBT-LuSrus3_Xz58qsTGdhtW6eRHaJX3R5rNDPiYZmBHKQv7Q5OyVxsX0BBJ7LOYy40SuldliDxXQjzEc8SBMdeoBS2XFrTqi6SToQ3PP8AIEHuqrHwxij8BoLXbn3Oqkb3A4XT8XjytTL1nsFaHszoGyj1taQpgG5ECkASfDrfbsvRzML7uZB5s0HWcWPWtAL7OM4GEJUvFwYJWg7U3bKu98YXuUKMP_6Wgbfg).
    * Use this Unsplash photo: [View of Earth from an Airplane](https://unsplash.com/photos/a-view-of-the-earth-from-an-airplane-WfhF41ZM2dc).
    * Set it as your **custom background** in the **new tab** extension settings.
**[OPTIONAL][BetterFox](https://github.com/yokoffing/Betterfox)**
* Make Firefox **faster, more private and secure** — without using third-party code.

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
