---
layout:     post
title:      Minor Fixes and Subscriptions
date:       2021-05-13 18:45:58
categories: info
---

v7.2.1

## Overview
We are releasing a patch of v7.2. This includes minor fixes for meal plans,
community images, and web subscription cancellations.


## Details
### ios
* Fixed: Currently active meal plan: Free users able to track meal plans from tracker screen
* Fixed: `Use this Plan` button does not respond after first time.
* Fixed: Deleting a meal plan from search results does not respond. 
* Fixed: Meal Plan Deeplink needs to handle `meal-plan?id=`
* Fixed: Deeplinks in Production App are not working for meal plans (crash)
* Fixed: Deeplinks do not always work

### android
* Fixed: Synchronization error. Please try again later
* Fixed: Images don't load appropriately on the Community
* Fixed: Meal Plan Upgrade: After upgrade the PRO banner is not updated on the Tracker screen.
* Fixed: Recipes search with filters
* Fixed: Meal Plan Create/Edit: Recent List is not displayed under "Results"
* Fixed: Meal Plan Deeplink should not be `meal-plan` and should be `mealplan`
* Fixed: Grocery List only gets first ingredient from custom recipes
* Fixed: Implement Unified Deep Linking for AppsFlyer
* Fixed: Deeplinks do not always work

### api
* API Stripe Renewals are not reflected in user's accounts
* Users cannot cancel their web subscriptions
