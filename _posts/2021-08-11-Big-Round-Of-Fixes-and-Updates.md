---
layout:     post
title:      Big round of fixes and updates
date:       2021-08-11 13:57:30
categories: info
---

v7.5.2

## Overview
This patch release fixes a lot of issues introduced in v7.5. v7.5 included a lot of major refactoring of code, which had a few ripple effects we had to address. In addition, we also added fixes for a lot of old issues that started to appear more recently.

The big ones to note are: deep links from within the community on iOS now work, the bell and community icon badges are now updated appropriately, Coffee Creamer doesn’t mysteriously show up anymore, and a lot of Android 10 and Android 11 bugs.

### Deep Links
For iOS, some app browsers do not allow deep links to open up in other apps. For example, sometimes if you share an iTrackBites community post on WhatsApp, their internal browser sometimes does NOT allow you to open up the iTrackBites app, and instead you are taken to the App Store. This is something we can’t control.

Please note that we are now handling links within the app, and also have successfully tested internal browsers in apps like the Messages app, Slack, Instagram, Facebook, Facebook Messenger, and a few others.

## Details
### api
- Comment notifications now say “comment” instead of “post”

### ios
* Fixed: Deep links from the community do not always work when linking to a post
* Fixed: The Meal Plan `Use this Plan` button does not respond after “Upgrade” pop up
* Fixed: Back doesn’t work: Start using the Plan from Community
* Fixed: Tapping a post in a user’s profile opens up previous post
* Fixed: On recipe page, mismatch between favorites carousel and “see all” favorites
* Fixed: Menu bar disappears after making a new post
* Fixed: Bell and Community icons are not showing badge when there are unread notifications
* Fixed: `Add to Meal Plan` option not available when using recipe search
* Fixed: `Add to Meal Plan` option not available for `see all` screen
* Fixed:  `Email us` link in the settings screen does not respond
* Fixed: Scanner: When food not found, creating a new food always shows as “Coffee Creamer”

### android
* Fixed: Upgrading on Android Tablets crashing
* Fixed: Mismatch of meal plan details screen between search and current active meal plan
* Fixed: Chrome/Firefox/Android 11: Fitbit does not sync after first time
* Fixed: Android 10: App crash after tapping item from the food search list
* Fixed: On recipe page, mismatch between favorites carousel and “see all” favorites
* Fixed: Bell and Community icons are not showing badge when there are unread notifications
* Fixed: Notifications count not updated after read/unread when using “Mark all read”
* Fixed: Android 11: Search meal plan keyboard blanks out the screen content
* Fixed: Recipes: `Add to Meal Plan` option not available under `See All`
* Fixed: Android 11: `Email us` in the settings screen does not respond
* Fixed: Invite Friends: Bad request error

