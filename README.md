<div align="center">
    <h1>Firefox Userstyle</h1>
</div>

This style is a one-line way to make Firefox minimalistic and more visually appealing. I use this style on my personal Firefox setup. Feel free to customize it further to suit your preferences.

No colors / themes are included, as I prefer to use separate themes/extensions for that purpose.

## Installation

1. Open your profile folder
   - In Firefox go to `about:support` → "Profile Folder" → "Open Folder".

2. Enable custom styles
   - In `about:config` set `toolkit.legacyUserProfileCustomizations.stylesheets` = `true`.
   - Restart Firefox.

3. Clone the style
     ```
     git clone https://github.com/s4nj1th/firefox-css.git" chrome
     ```

4) Make sure the main file is named correctly
   - Place `userChrome.css` (for browser UI tweaks) and/or `userContent.css` (for webpage tweaks) directly inside the `chrome/` folder (or ensure your repo does this for you).

5) Restart Firefox
   - Close all Firefox windows and relaunch. Your style should load.

## Screenshots

![screenshot1](./screenshots/01.png)
