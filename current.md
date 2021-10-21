---
layout: page
title: Current Status
permalink: /current/
---

_Updated 10/21/2021 15:12 PT_

v7.7.1 has been released to the App Store and Google Play Store.

In v7.7.2, we will be addressing the issue of custom recipes/favorites/recents having some zero bite food items showing with bite counts in an upcoming v7.7.2 release. This is top priority and the next release will include the fix. The fix is extremely complex so it’s going to take a lot of engineering and testing to ensure it works on both iOS and Android. There’s no time estimate yet, because we haven’t found a viable solution yet, but once we do, we’ll be able to give a better estimate.
I’m hoping we can get this done in 3 - 7 days, with a release shortly after full testing (and beta testing from all of you if possible!).

- All new custom recipes, recents, and favorites will not be affected as long as users are on v7.1.1
- Tracking from custom recipes/favorites/recents will still work correctly, even though the initial bite counts are showing as more than zero.
- Users can toggle the 0 Bites? option when tracking or adding to recipes to trigger the re-calculation of bites correctly as a workaround for the time being.
- The new fix will run a script through all recents/favorites/custom recipes on everyone’s devices to essentially recalculate and save those values so they will appear correctly when viewing.

***

### Upcoming Releases
- 7.7.2.  - 3 to 7 days
- v7.8    - October 27, 2021
- v7.9    - November 17, 2021
 
### Past Releases
- v7.7    - October 7, 2021
- v7.6    - Android: September 17, 2021, phased rollout started for 5 days.
- v7.6    - iOS: September 15, 2021 phased rollout started for 7 days.

***

### Known Issues

|Issue                          |Platform   | Status    | Release           |
| ---                           | ---       | ---       | ---               |
|Existing Custom Recipes and favorites show BITES for ZERO food items|iOS/Android|investigating| v7.7.2|
|Recipes/Custom recipes: Serving sizes not displayed on meal detail overlay |iOS/Android|ready for QA| v7.8|
|"Add to Meal Plan" option to be shown right after adding custom food/recipes |iOS|ready for QA| v7.8|
|Share: Community needs a refresh to load posts |Android|ready for QA| v7.8|
|Results tab: Restaurant foods do not adhere to zero bite ingredients |iOS/Android|ready for QA| v7.8|
|Android 11: Export log does not trigger any option to select email |Android|ready for QA| v7.8|
|"Add to Meal Plan" option not available when using recent list (Recipes) |Android|ready for QA| v7.8|
|Alcohol bites not calculated correctly for Carb Conscious weight loss plan users |iOS/Android|ready for QA| 7.8|
|Editing post does not retrieve the data on the same page |Android|ready for QA| v7.8|
|Click error on tapping video on the community |Android|ready for QA| v7.8|
|Stay on the food search results page after tracking|iOS|ready for QA| v7.8|
|Update serving size decimals to match iOS|Android|ready for QA| v7.8|
|iOS 15 UI Issues|iOS|ready for QA| v7.8|
|Meal Plan's meal titles do not show the first item in the meal plan, but the photo shows the first one |Android|ready for QA| v7.8|
|Posts should include "close comments" option |iOS|ready for QA| v7.8|
|Facebook & Facebook Messenger Sharing Options not shown  |Android|ready for QA| v7.8|
