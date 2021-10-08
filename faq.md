---
layout: page
title: FAQ
permalink: /faq/
---

_Updated 10/08/2021 11:38 PT_

## Phased Rollouts

We release new versions of the app in phases to percentages of our users of the course of a week. We do this to ensure that any major bugs that we might have missed in QA are not immediately released en masse. Please read below for details on how phased rollout works on iOS and Android.

### Summary

- Each day a percentage of new and existing users will have the opportunity to
  automatically get the latest update
- At the end of the rollout, all users will get access
- iOS users, even if they are not in the current rollout, **can manually update** from the AppStore, but not automatically
- Android users **cannot** get the update until they are part of the phased rollout
- Best practice: assume the stricter rules of Android when announcing to the
  general community, that there is no way to update.

***

### iOS Behavior

On iOS, the version update will be released over a 7-day period to a percentage of users (selected at random by their Apple ID) with automatic updates turned on. Users won't be notified if they receive a version of our app in a staged rollout. All users who have downloaded the app will still be able to update the app manually from the App Store at any time. New users who download the app will get the latest version of the app as well.

|Day of Phased Release      |Percentage of Users      |
| ---                       | ---                     |
|1  |1% |
|2  |2% |
|3  |5% |
|4  |10% |
|5  |20% |
|6  |50% |
|7  |100% |

### Android Behavior

On Android, the version update will be released over a 7-day period to a percentage of users selected at random. Users will be notified if they receive a version of our app in a staged rollout. Users won't be able to manually download the latest version and must wait until they are in the group of users selected for the rollout. New users will also be randomly selected for the new version of the app according to the percentage of users the new version is available to on the day of phased release. 

|Day of Phased Release      |Percentage of Users      |
| ---                       | ---                     |
|1  |1% |
|2  |2% |
|3  |5% |
|4  |10% |
|5  |20% |
|6  |50% |
|7  |100% |

***

## Notification Limtis

We currently cap the number of email and push notifications that can be sent within a certain time period in order to protect our users from spam.

Please see the current time limit caps below:
- Push = limit 1 push notification every **5** minutes
- Email = limit 1 email notification every **10** minutes

Note that if a push or email notification is triggered within the time limit, no notification will be sent (even after the time limit is up).

These limitations do NOT apply to in-app community notifications! Users should receive notifications for every event triggered in their community notifications page.

***

## Sharing and Deeplinks

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
