# Web Home

This repo is my custom Chrome home / new tab page

# Set Up

1. Enter this into the Chrome URL address bar
```
chrome://extensions/
```

2. Enable developer mode using the toggle near the top right of the page

3. Select "Load unpacked" and then select this repo's folder

4. By default, Chrome will always focus on the address bar (aka omnibox) whenever you open a new tab. It is possible to work around this by using a redirect. If this is desired, go to manifest.json and apply the following option

```
"chrome_url_overrides": {
    "newtab": "newtabfix.html"
}
```