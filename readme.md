# Theme Collection
Aimed to be as striaght forward as possible to customize yourself.
I've designed all these themes to work with the standard [root.css](root.css) file so people can just change the colors as they wish. I believe strongly in freedom to modify applications, and CSS with some proper management of variables is a great way to do that.
> You can use a browser extension like [Stylus](https://addons.mozilla.org/en-CA/firefox/addon/styl-us/) to modify CSS on webpages.
## Firefox Theme
The [manifest.json](manifest.json) file is the only thing related to the theme in Firefox that matches the [root.css](root.css). You can load this file into Firefox without uploading it to the store using the `about:debugging` url. I've published it to the store [here](https://addons.mozilla.org/en-US/firefox/addon/poeko-theme/), however if you use a custom css root and don't want to use the `about:debugging` url every time Firefox boots you'll have to upload your `manifest.json` as a `.zip` to Firefox store.
## Home Assistant Theme
Please refer to the Home Assistant official documentation ..<br>
https://www.home-assistant.io/integrations/frontend/#themes
> Note that my Home Assistant theme is currently broken, it's on my todo list!<br>
> It works in dashboards but gets weird in the automations screen since the rework of that UX.
## Logseq Theme
Using the same [root.css](root.css) configuration we can setup [Logseq](https://logseq.com) to match everything. I've tried to make the [custom.css](logseq.css) simple, so this file only affects the dark theme under accent color `none`. The [export.css](logseq.export.css) that I have just hides things that aren't helpful in the html preview, it doesn't add any styling. If you have multiple graphs in LogSeq that you want to theme you can save the [custom.css](logseq.css) and [export.css](logseq.export.css) anywhere on your computer and then import the asset into each graphs `custom.css` and `export.css` by adding something like this line to them;
```
@import url('file:///C:/Users/yourusername/path/to/css/logseq.css');
```
Make sure to use the **full path** of the CSS files and the correct filename for *export* or *custom*.
