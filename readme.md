# Theme Collection
Aimed to be as striaght forward as possible to customize yourself.
I've designed all these themes to work with the standard `root.css` file so people can just change the colors as they wish.
### Adding CSS to Browsers
You can use a browser extension like [Stylus](https://addons.mozilla.org/en-CA/firefox/addon/styl-us/), here's their [homepage](https://add0n.com/stylus.html).
### Firefox Theme
The `manifest.json` file is the only thing related to the theme in Firefox that matches the `root.css`. You can load this file into Firefox without uploading it to the store
using the `about:debugging` url. My theme is available [here](https://addons.mozilla.org/en-US/firefox/addon/poeko-theme/), however if you use a custom css root and don't want
to use the `about:debugging` url every time Firefox boots you'll have to upload your `manifest.json` as a `.zip` to Firefox store.
### Home Assistant Theme
Please refer to the Home Assistant official documentation ..<br>
https://www.home-assistant.io/integrations/frontend/#themes
### Logseq Theme
Using the same root configuration we can setup logseq to match everything. I've tried to make the `custom.css` simple, so this file only affects the dark theme. The `export.css` that I setup just hides things that aren't helpful in the html preview, it doesn't add any styling. If you have multiple graphs in LogSeq that you want to theme you can save the `custom.css` and `export.css` anywhere on your computer and then import the asset into each graphs `custom.css` and `export.css` by adding something like this line to them;
```
@import url('assets:////C:/Users/username/notes/custom.css');
```
Make sure to use the **full path** of the files and the correct filename for *export* or *custom*.
