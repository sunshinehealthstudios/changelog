---
layout:     post
title:      Streaks Resets Fixed, Water Tracker, and Recipes (iOS)
date:       2024-08-28 15:36:24
categories: info
---

v9.2 (iOS)

## Overview

We have made a big change on how streaks are recorded and processed in order to solve multi-device, syncing, and incorrect resetting. We have a brand new custom water tracker, as well as a big fix to all recipe BITE counts and calories.

## Details

### iOS
* New: Custom water tracker on the tracking screen, allows for custom water
  goals and measurements.
* Fixed: Overhaul of Streaks system that tracks all streaks on the API, removing
  the dependency on syncing across multiple devices, app upgrades, and data
connection strength.
* Fixed: Recipe BITES, Calories, and netcals are now all updated. These counts
  were not accurate before, but the issues have now been resolved.
* Fixed: Featured Recipes only show 26 items. Now they will paginate.
* Fixed: When not using decimals, calculator no longer shows a decimal point
* Added: Streaks can be completely hidden now from the tracking screen by
  changing it in settings.
* Added: Water tracking can be completely hidden from tracking screen in the
  settings
* Changed: Remove `oz` weight unit and rename `fl oz` to `oz`
* Fixed: Add to Meal Plan - Featured Recipe does not have an option to previous
  screen without adding to meal plan
* Fixed: Custom recipes allowed people to save recipes still, but it should only
  allow favoriting.
* Fixed: Do not clear the search term when cancelling search and selecting
  another search tab.
* Fixed: Add to Recipes - when tapping `x` to cancel the search, the default
  screen is not displayed
* Fixed: Create Food - after tracking created food using barcode scanner, the
  create food screen does not get dismissed.

