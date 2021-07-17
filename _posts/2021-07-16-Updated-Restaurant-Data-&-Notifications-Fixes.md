---
layout:     post
title:      Updated Restaurant Data & Notifications Fixes
date:       2021-07-16 17:33:30
categories: info
---

v7.5

## Overview

In this release, we’ve fixed issues regarding notifications, bite calculations, user blocking, and restaurant search. We’ve also updated our restaurant data to include more restaurants and the latest menu offerings.

## Details

### api
* Updated restaurant data
* Fixed: Unable to post on certain groups
* Fixed: Some restaurants do not show any items & others are incorrectly labeled as having "0 items"


### ios
* Fixed: Weeklies Mismatch on the tracker screen after weigh in
* Fixed: Zero BITES food items not calculated as 0 when added to meal plan
* Fixed: Snack & Beer items from Brands tab not added to meal plan
* Fixed: Adding restaurant items to meal plan shows "0" BITES after saving
* Fixed: Profile picture and weight loss plan icon not appearing correctly on notifications
* Fixed: Not receiving any notification when posting on a group
* Fixed: Certain tracked foods do not open the food details screen
* Fixed: Blocked users can comment on previous community posts even after being blocked
* Removed restaurant search case and formatting sensitivity
* Removed post types: Recipe, Milestone, Spoonacular Recipe, Meal Plan 
* Updated restaurant search placeholder text
* Updated search placeholder text
* Fixed: Deleting meal plan does not respond on user profile
* Fixed: When editing a meal plan, tracking food during modification dismisses the edit mode
* Added display text on meal plan edit mode when a day has no meals
* Fixed: Total sum of BITES not correct when modifying a custom recipe


### android
* Fixed: Weeklies Mismatch on the tracker screen after weigh in
* Fixed: Zero BITES food items not calculated as 0 when added to meal plan
* Fixed: Profile picture and weight loss plan icon not appearing correctly on notifications
* Fixed: Only future notifications should be shown after joining a group
* Fixed: Search meal plan blanks out screen content on Android 11
* Fixed: Unable to enter phone verification code as keyboard doesn't show up
* Fixed: App crashes on tapping tracked food/restaurant items
* Fixed: Free users are able to track meals from tracker screen even after PRO has expired
* Fixed: App crashes on tapping food items from recent/search results
* Fixed: App crashes on barcode scanning
* Fixed: Click error on tapping on a video in the community 
* Removed restaurant search formatting sensitivity
* Fixed: Changes to Favorite status not reflected on foods that come from online sources
* Fixed: Cannot close out bar scanner screen
* Removed post types: Recipe, Milestone
* Fixed: Checked items on the grocery list not remembered after navigation
* Fixed: Featured meal plans displayed without images
* Updated search placeholder text 
* Fixed: Unable to remove favorites from posts shared on the community
* Fixed: BITES mismatches before/after saving a new recipe & mismatched total BITE count
* Fixed: Cannot save a meal plan when editing a custom meal plan from the community
* Fixed: Featured recipes does not sync under "favorites" recipes menu

