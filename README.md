# Migrate WebView LocalStorage data from file-urls to localhost

## Installation ##

```bash
cordova plugin add https://github.com/davidpadych/cordova-plugin-migrate-localstorage-ionic
```

## Paths ##

Android UIWebView

```bash
old: file:///android_asset/www/index.html
new: http://localhost
```

iOS UIWebView -> WKWebView

```bash
old: file://...
new: ionic://localhost
```
