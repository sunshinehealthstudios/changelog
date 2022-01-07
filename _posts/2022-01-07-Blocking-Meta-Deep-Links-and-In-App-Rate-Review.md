---
layout:     post
title:      Blocking, Meta Deep Links, and In-App Rate & Review
date:       2021-01-07 13:15:37
categories: info
---

v7.11

## Overview
This release includes fixes to user blocking, sharing links on Meta apps, and improves how users rate and review the app. On iOS, it also fixes a bug where the date in the app would not automatically advance to the next day. On android, fixes an issue with ingredients/directions appearing on spoonacular recipes. 

## Details
### api
* Fixed: Blocking users doesn't work as expected

### ios
* Updated: In-app rate and review
* Fixed: Blocking users doesn't work as expected
* Fixed: Improve deep link sharing on facebook apps
* Fixed: Editing comments with emojis jumps to the end of the text
* Fixed: Secondary metrics still show for free user after cancelling subscription
* Fixed: Rating rating: bad request message appears
* Fixed: App not advancing to thre next day automatically on the tracker page	
* Fixed: Barcode scanner keeps spinning when barcode incorrect or not found
* Fixed: Occasionally tick mark does not appear when tracking meals
* Fixed: PRO banner not shown for free user
* Fixed: Modified foods filters special characters on search results


### android
* Updated: In-app rate and review
* Fixed: Blocking users doesn't work as expected
* Fixed: Improve deep link sharing on facebook apps
* Fixed: Ingredients/Directions Incomplete on Spoonacular Recipes
* Fixed: Secondary metrics still show for free user after cancelling subscription
* Fixed: New notifications appear at the bottom of the screen
* Fixed: Navigating back while creating a recipe closes out the screen
* Fixed: User is allowed to create account with same email address (case-sensitive)
* Fixed: Edit meal plan dismessed & app closed out on screen timeout/device lock
* Fixed: Community Sharing: insertion pointer not on focus while typing	
* Fixed: Incorrect alerts for comments closed	
* Fixed: Email us displays incorrect app version
* Fixed: Meal plan upgrade: wrong upgrade screen appears
* Fixed: On custom recipe multi-selecting ingredients shows total bites as 0	
* Fixed: Custom food gets duplicated after adding to meal plan	

