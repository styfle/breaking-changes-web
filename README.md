<img width="200" height="128" src="https://i.imgur.com/UZ5yFcp.jpg" align="right">

# Breaking Changes to the Web Platform

Over the years there have been necessary changes to the web platform that caused legacy websites to break.

Below is a list of those changes.

* SSL removed in favor of TLS [wiki](https://en.wikipedia.org/wiki/Transport_Layer_Security#SSL_1.0,_2.0,_and_3.0) (June 2015)
* Adobe Flash (SWF) End of Life [wiki](https://en.wikipedia.org/wiki/Adobe_Flash#End_of_life) (December 2020)
* `<applet>`, `<blink>`, and many other tags removed [html5](https://www.w3.org/TR/html5/obsolete.html) (January 2008)
* `window.showModalDialog` removed [operablog](https://dev.opera.com/blog/showmodaldialog/) (August 2014)
* Passive touch listeners by default [googleblog](https://developers.google.com/web/updates/2017/01/scrolling-intervention) (January 2017)
* Forms with passwords marked `Not Secure` over HTTP [googleblog](https://security.googleblog.com/2016/09/moving-towards-more-secure-web.html) (January 2017)
* ~~`Array.prototype.flatten` breaks MooTools [bugzilla](https://bugzilla.mozilla.org/show_bug.cgi?id=1443630)~~ [renamed](https://developers.google.com/web/updates/2018/03/smooshgate) to `Array.prototype.flat` (May 2018)
* Full page layout is no longer synchronous [googleblog](https://developers.google.com/web/updates/2018/07/site-isolation#full-page_layout_is_no_longer_synchronous) (May 2018)
* HTML Imports (part of Web Components v0) deprecated [googleblog](https://developers.google.com/web/updates/2018/09/chrome-70-deps-rems) (October 2018)
* WebSQL is removed [developer.apple.com](https://developer.apple.com/documentation/safari-release-notes/safari-13-release-notes) (September 2019)
* Cookies changed from `SameSite=None` to `SameSite=Lax` by default [chromestatus](https://www.chromestatus.com/feature/5088147346030592) [tweet](https://twitter.com/simonw/status/1422366158171238400) (August 2020)
* `alert()` and `confirm()` removed from cross-origin iframes [chromestatus](https://www.chromestatus.com/feature/5148698084376576) [tweet](https://twitter.com/chriscoyier/status/1420027533005836298) (July 2021)
* Removing HTTP/2 Server Push from Chrome [chromeblog](https://developer.chrome.com/blog/removing-push/) (August 2022)
