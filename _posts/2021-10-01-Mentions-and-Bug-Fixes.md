---
layout:     post
title:      Mentions & Bug Fixes
date:       2021-10-01 17:56:57
categories: info
---

v7.7

## Overview
This release includes a new mentions feature on our community. Users will now be able to tag other uses in a mention and users will be notified when they are tagged in a mention. We have also fixed bugs on our Conquer Cravings plan that were causing incorrect bite counts on custom foods. Lastly, we have made improvements to hashtags and deep links.

[Video explaining new mentions feature](https://drive.google.com/file/d/1YfGniE4M2sxow0DFK0omtLuJ-vHZP-pB/view?usp=sharing)

## Details
### api
* Fixed: Results tab: Zero BITE food items are displayed with non-Zero BITES
* New Feature: Transactional in-app, push, and email notifications for mentions

### ios
* New feature: @mentions
* Fixed: Conquer Cravings Custom Food: Default BITES values are displayed as Zero after saving
* Fixed: Hash Tags do not filter/redirect appropriately
* Fixed: Meal Plan Comments: Keyboard not to be dismissed after selecting the mentions
* Fixed: Tracker Screen: Occasionally the "Tick" mark is not updated appropriately
* Fixed: Hashtags do not link correctly in meal plans and comments

### android
* New feature: @mentions
* Fixed: Custom Food: Input on default BITES and Calories does not calculate appropriate BITES after Saving
* Fixed: Custom recipe: Sometimes we get error message on saving recipe
* Fixed: Hash tags do not redirect appropriately on push notifications
* Fixed: Deleting favorited food from "Recent" list removes from Favorite tab
* Fixed: Add option to remove food from Recents during a search
* Fixed: Posting text only (no media or mentions) causes the app to crash
* Fixed: Hashtags do not link correctly in meal plans and comments
* Fixed: Hexagon not appearing properly on Calorie Command or Keeping Keto
* Fixed: Snacks: BITES mismatch between overlay and details screen
* Fixed: Android 11: Crashing when clickling community or profile pages
