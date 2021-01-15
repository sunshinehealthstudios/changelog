---
layout:     post
title:      Meal Plan Fixes
date:       2021-01-20 04:36:18
categories: info
---

v7.0.1

## Overview
This is a minor release that we made to address some server issues from both
meal plan release but also in some of the increased use and the amount of new
users we've had sign up this year so far.

## Details

### api
* Fixed - There were some server timeouts when starting the app for syncing
  account information, thus sometimes settings, custom recipes/foods were not
showing up.
* Fixed - Server Timeouts for API calls caused by php-fpm calls to nutritionix
  which caused overall server slowness, including Community posts and searching
for foods to track.

### android
* Fixed - Manual Allowance: Settings disappear from Tracker screen or toggle revert back
* Fixed - Discover PRO: Upgrade screen does not reflect the discounted price as in other screens
* Fixed - Phone verification does not approve even after providing valid verification code
* Fixed - Meal Plans Community Post should include Meal Plan Creator name
* Fixed - BITES Values inconsistent between iOS & Android
* Fixed - Opening a deep link on a browser redirects to the Play Store 
* Fixed - Meal Plan User Count: Modifying start date decrements the user count
* Fixed - Sign up Onboarding: New user is unable to set up username.
* Added - Pin Post for Meal Plans in Community Tab - Android
* Fixed - Add Deeplink to Meal Plans tab
* Fixed - Manual Allowance - Modified values under "Settings" are not saved appropriately.
* Fixed - (Production) Tracker: Zero BITES meal details screen shows different BITES values 
* Fixed - Google Pixel 3XL: Unable to access Calendar drop down.

### ios
* Fixed - BITES - To remove the special character from the value displayed.
* Fixed - Shared Meal Plan Post: Tapping on the meal plan post from Comment screen does nothing
* Fixed - Meal Plan BITES: Changing weight loss plan does not update the current meal plan BITES accordingly
* Fixed - Meal Plan User Count: Modifying start date decrements the user count/Inconsistency between explore screen.
* Added - Pin Post for Meal Plans in Community Tab - iOS
* Fixed - Collapsible calendar - Blank insignificant space occur after upgrade.
* Fixed - "PRO" Upgrade - PRO Member since "date" mismatch.
* Fixed - (Production) Tracker: Zero BITES meal details screen shows different BITES values 
* Fixed - Add to Next day: By default it should add to the today's date
