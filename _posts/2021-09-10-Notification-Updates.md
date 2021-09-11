---
layout:     post
title:      Notification Updates & Conquer Cravings Fiber Cap
date:       2021-09-10 21:01:57
categories: info
---

v7.6

## Overview
We have updated our notifications in order to notify users for only the most salient posts and comments. Please view the video linked below for an in-depth explanation of how notifications should work now. We have also fixed the 4g fiber cap for Conquer Cravings.

## Details
### api
* Update notification text to differentiate between posts and comments
* Limit 1 notification for new posts
* Limit 1 notification for new comments
* Only post owners will receive notifications for comments on a thread
* After a joining a group, only future activity of the group is received as notifications.
* Updated group notification logic so that members will only receive notifications for new group posts (not comments)

Video explaining notification logic updates:
https://drive.google.com/file/d/1L0cJA-Fewv5-YwkNlWrSca9I8AytH1S-/view?usp=sharing 

### ios
* Update notifications read/unread behavior
* New feature: ability to edit serving sizes on items added to meal plan
* Hide bites for custom recipe ingredients unless in edit mode
* After tracking a meal, "tracked" message should appear
* Fixed: custom recipe BITES mismatch with serving size pop up
* Fixed: Meal detail overlay serving sizes are not listed/inappropriate
* Fixed: Recipes BITES mismatch with meal detail and "Recipes" screen
* Fixed: serving size on tracker does not match the modified serving size
* Fixed: updating a meal plan start date is not working
* Fixed: meal plan tabs disapppear after tracking food or custom food
* Fixed: foods and custom foods do not close properly after tracking
* Fixed: Meal items to be separated by , instead of ;
* Fixed: Edited Serving Sizes of Searched Foods Not Saving in Meal Plan
* Fixed: Default serving size values for recipes is not retrieved appropriately on track screen
* Fixed: Total Meal Day BITES discrepancy with custom foods
* Fixed: Calories mismatch between "Edit Serving Size" screen and "Food Details" screen
* Fixed: Bites hexagon displayed as blank on serving size overlay
* Fixed: Unable to open "Edit Serving Size" screen after adding recipes to the meal plan
* Fixed: BITES values not updated while changing serving size values
* Fixed: Edit serving size dismisses the meal detail overlay
* Fixed: Serving Size: Measurements/categories does not match as that of the "Edit Food" screen.
* Fixed: Hummus BITES inconsistency with Android
* Fixed: Conquer Cravings bite calculation needs to adhere to 4g Fiber Cap
* Fixed: "Bad request error: Meal Plan not found" message appears

### android
* Update notifications read/unread behavior
* New feature: ability to edit serving sizes on items added to meal plan
* Hide bites for custom recipe ingredients unless in edit mode
* After tracking a meal, "tracked" message should appear
* Fixed: Custom Recipes added to meal plan at "SNACK" gets set into "BREAKFAST" instead
* Fixed: recipe ingredients incorrect quantitiy on grocery list
* Fixed: Hitting "save" or "track" on a meal plan should redirect back to "Your Meal Plan"
* Fixed: unable to remove custom food from meal plan
* Fixed: Total Meal Day BITES discrepancy with custom foods
* Fixed: Meal items to be separated by , instead of ;
* Fixed: custom recipe BITES mismatch with serving size pop up
* Fixed: Recipes BITES mismatch with meal detail and "Recipes" screen
* Fixed: Non-Edit Meal Plan Mode: Missing "Track" button and seeing "Save"
* Fixed: App Crash: When trying to add image to meal plan
* Fixed: Add Zero BITES food shows non-zero value while modifying the serving size
* Fixed: Meal item images not displaying on meal plan
* Fixed: "Edit Serving Size" not displayed when adding custom foods
* Fixed: Android 11: "See All" under Beers crashes the app
* Fixed: Android 11: Speech recognition services not working
* Fixed: Conquer Cravings bite calculation needs to adhere to 4g Fiber Cap
* Fixed: Unable to open app after recent Android build update
* Fixed: Password Reset Link Doesn't Work
* Fixed: Meal Plan tabs aren't visible on night mode
