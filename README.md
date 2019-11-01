<h1 align="center">chrome-extension-dl</h1>
<p align="center">A script that downloads chrome extensions</p><br>

The goal of this project is to implement a script
that makes downloading chrome extensions convenient.
It is intended to be used with [ungoogled chromium](https://github.com/Eloston/ungoogled-chromium).

<br>

## Usage


```sh
NAME
chrome-extension-dl - install chrome extensions

SYNOPSIS
chrome-extension-dl [url]
chrome-extension-dl --presets [file]
chrome-extension-dl update

DESCRIPTION
chrome-extension-dl Download extensions from chrome webstore.

Set CHROME_EXTENSIONS_DIR to change extensions folder.


Install Guide:
1. Visit chrome://extensions in your browser.
2. Ensure that the Developer mode checkbox in the top right-hand corner is checked.
3. Click Load unpacked extension... to pop up a file-selection dialog.
4. Navigate to /home/th3lusive/.local/share/chrome-extensions/, and select it.
```

## Credit

- [inoxunpack](https://github.com/gcarq/inoxunpack)
- [ungoogled chromium](https://github.com/Eloston/ungoogled-chromium)
- [pure-sh-bible](https://github.com/dylanaraps/pure-sh-bible)
