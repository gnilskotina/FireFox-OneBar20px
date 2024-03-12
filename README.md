<div align="center">
    <br><h1>FireFox OneBar20px</h1></br>
</div>

# Description📋
This is my fork of a single bar for Firefox's UI, but bar so 20px (so small😁).
<details><summary>Demo</summary>

![demo](https://i.imgur.com/LRkLgnQ.png)</details>

# Installation

#### In Firefox
- Firstly, make sure you are on the latest firefox stable version. ESR & other editions may not work as intended.
1. Visit `about:config` 
    - Search for `toolkit.legacyUserProfileCustomizations.stylesheets`, set it to **true**
    - While you're here, [you can enable other customizations you may want here](#customizations)
2. Visit `about:support`
3. In the `Profile Directory` row, copy the full path
    - May look something _like_: `/home/{username}/.mozilla/firefox/...`

#### Then, in a Terminal
Run each line individually
```sh
cd #paste the path you copied before here

git clone https://codeberg.org/Freeplay/firefox-onebar.git chrome
```

#### OR, to add it manually:
1. Go to the path you copied before in your file explorer
2. If there is no `chrome` folder, create one
3. Then, inside the `chrome` folder, create a file called `userChrome.css`
    - Copy & Paste the contents of [`userChrome.css`](https://codeberg.org/Freeplay/Firefox-Onebar/raw/branch/main/userChrome.css) into the file

#### Restart Firefox, and enjoy :)

*Firefox 121.0*
