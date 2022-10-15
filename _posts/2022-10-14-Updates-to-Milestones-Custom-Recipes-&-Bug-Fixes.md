---
layout:     post
title:      Updates to Milestones, Custom Recipes, & Bug Fixes
date:       2022-10-14 03:19:37
categories: info
---

v7.19

## Overview

This release includes an update to our badges & milestones. We have added more milestones for users to meet and users will now be able to order the badges they have achieved for free on our shop.

We have improved our recipe creation flow to prevent users from accidentally abandoning an in progress recipe without saving. We also made some UI improvements to custom recipes so that bites are shown for individual ingredients.

Lastly, we have fixed a few bugs seen on iPad, reduced loading time on our groups pages, and fixed an issue with loading search results on Android.

[Milestone & Badge Updates Walkthrough](https://drive.google.com/file/d/1vUOahWeOJiA4JpJJRM1pPPHlLwWNpeyT/view?usp=sharing)

[Custom Recipe Updates Walkthrough](https://drive.google.com/file/d/1BbZtXekLuGDJI0tmC1lCfuHGcTPVPvwU/view?usp=sharing)


## Details

### api
* Fixed: Groups with 0 members are being displayed in the Group's list
* Fixed: Groups: members without names are being displayed in the member's group list
* Fixed: High latency when loading groups
* Fixed: Deleting a group emails support asking for a reason

### ios
* Updated: Update badge images & milestones
* Updated: UI Updates on Custom Recipes Screen
* Updated: Update recipe share screens
* Updated: Add warning message for abandon custom recipe flow
* Updated: Update upgrade screens to be contextual
* Updated: Replace Explore PRO upgrade screens 
* Updated: Update brands tab paywall
* Updated: Update empty state of "My Groups"
* Fixed: Bites on custom foods automatically become overrides
* Fixed: Improve loading on group search
* Fixed: iPad: Blank screens on Activity, Comments, & Blog
* Fixed: App crashes when editing custom recipes 
* Fixed: Progress Chart doesn't show all achieved badges
* Fixed: Progress chart: tracked food shows "no food logged"

### android
* Updated: Update badge images & milestones
* Updated: UI Updates on Custom Recipes Screen
* Updated: Update recipe share screens
* Updated: Add warning message for abandon custom recipe flow
* Updated: Update upgrade screens to be contextual
* Updated: Replace Explore PRO upgrade screens 
* Updated: Update brands tab paywall
* Updated: Update empty state of "My Groups"
* Updated: Add link to cancel subscription
* Fixed: Bites on custom foods automatically become overrides
* Fixed: Free users are able to access restaurant foods on brands tab
* Fixed: Items do not fully load with smart search ON
* Fixed: PRO status not reverted back after subscription expires
* Fixed: Unable to share active meal plan to community
* Fixed: Carb Conscious: bites on calculator change when retyping same values
* Fixed: Timeout when saving a recipe
* Fixed: App crashes when tapping on community tab
* Fixed: App crashes when user taps on the Meal Plans tab 
* Fixed: Incorrect BITES on items with "floz"
