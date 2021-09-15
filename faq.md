---
layout: page
title: FAQ
permalink: /faq/
---

_Updated 09/14/2021 18:47 PT_

***

### To Note Before Troubleshooting

In some cases, URLs may not perform the intended deep linking. When this happens, instead of opening the app or getting deep linked into a specific activity within the app, users are redirected to the app store or to an error page.

There are several possible reasons for this:

- Host applications: Apps (such as WhatsApp, Gmail, WeChat) use different methods to activate clicked links, such as proprietary internal browsers. Some of these are known to block all attribution links.
- Browsers: Certain browsers and OS platforms behave differently with links. In certain browsers, for example, pasting a link does not work. The link must actually be clicked.
- OS updates: New OS updates (both iOS and Android) may introduce unexpected bugs that hamper deep linking.
- Devices: Different smartphones, tablets, laptops, and other devices running different versions of iOS, Android, Windows Mobile, and other operating systems can vary greatly in their handling of attribution links. 

***

### Behavior: App Not Installed

Device will navigate to our App Store page. When a user installs and opens the app, (deferred) deep link data is passed into the app.


### Behavior: App Installed (iOS)

|Platform                          |Behavior   | 
| ---                           | ---       |
|iTB community post  |iTrackBites App|
|Safari Browser  |iTrackBites App|
|Safari Address Bar  |App Store (but there can be issues with the redirect, more info)|
|Chrome Browser  |iTrackBites App|
|Chrome Address Bar  |App Store|
|Brave Browser  |iTrackBites App|
|Brave Address Bar  |App Store|
|Gmail app  |iTrackBites App, but might show options to pick between in-app browser, Chrome, Safari, etc. depends on settings/experimentation group|
|Slack  |iTrackBites App, but must configure Slack to open links with Safari|
|Facebook Newsfeed  |App Store|
|Facebook Browser  |iTrackBites App|
|Facebook Messenger  |App Store|
|Instagram Profile  |App Store|
|Instagram Browser  |iTrackBites App|
|Instagram Stories  |App Store|
|Instagram Messages  |App Store|
|Threads  |iTrackBites App|
|Twitter App  |iTrackBites App|
|Twitter Browser  |iTrackBites App|
|Tweetbot  |iTrackBites App (when Safari is chosen in browser settings, or when Deep Links is enabled)|
|Snap Messages  |App Store|
|Snap Stories  |App Store|
|Reddit Messages  |App Store|
|Reddit Chats  |App Store|
|Apollo  |App Store|
|Pinterest  |App Store|
|Pinterest Browser  |iTrackBites App|
|Firefox Browser  |App Store|
|Firefox Address Bar  |App Store|
|LINE  |iTrackBites App|
|WhatsApp  |iTrackBites App|
|Discord  |App Store|
|Apple Mail |iTrackBites App|
|GitHub app  |iTrackBites App|
|TikTok  |App ads will send to App Store, other ads will open in-app browser|
|Message.app  |iTrackBites App|
|Google Hangout  |iTrackBites App|
|Google Voice  |iTrackBites App|
|Kakao  |iTrackBites App (it opens the deeplink in in-app browser, and then it launches app)|
|WeChat  |App Store|
|Signal  |iTrackBites App|
|Telegram |iTrackBites App|
