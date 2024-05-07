---
layout:     post
title:      Create Food Redesign and Image Quality Fix
date:       2024-05-07 14:12:03
categories: info
---

v8.10 (iOS)

## Overview

We have redesigned the create food screen slightly to match the new look of Healthi. We have also fixed the quality of images in the community when viewing them in the feed so they are higher quality like before. There also bug fixes for barcode scanning with BITES and macros.

## Details

### iOS
* New: Create Food redesign
* Fixed: Image quality on the main feed was very low. They are now much higher
  quality
* Fixed: After scanning a food item and tracking it, the scanner screen could
  not be dismissed.
* Fixed: BITES and Macros are fixed when tracking and scanning barcodes when
  there were rounding errors from grams vs other serving sizes
* Fixed: Streaks Post - unable to open the user profile after tapping image icon
* Fixed: When building a recipe, sometimes the user would be forced back to the
  tracker screen insetad of back to the recipe builder.
* Fixed: After scanning a barcode and changing serving size and tracking, the
  detail screen is not able to be dismissed.
* Fixed: Tracking food on a different date was not switching to that date on the
  tracker screen after tracking.
* Added: Zero BITES toggle added back to food details while tracking.

