---
layout:     post
title:      Community Meal Plans
date:       2021-04-27 21:39:26
categories: info
---

v7.2

## Overview
Meal Plans are getting a huge update! Now anyone can create and modify meal
plans. If you want to change a few details in a meal plan you're using, no
matter if you created it or if you got it from someone else, you can do it!
Add/remove any food item or recipe that you want.

Create and share your own meal plans. Create a meal plan that has worked for
you, and share it in our community, or through any other sharing app. Anyone can
use it, and also modify it to their needs as well.

Best yet, you can talk with the community about your meal plan that you're using
or you have created. Look for the "comments" tab within a meal plan to join the
conversation.

### Why
* Community is a huge part of what makes iTrackBites successful
* Community means people coming together for a reason. In this case, it’s to share, support, learn, and get motivated.
* Meal Plans will help people plan out their journeys, and instead of just being created by nutritionists, we want real community members to share what actually worked with them.
* Proof something works through science, but also through experience.
* A meal plan is so credible when someone real has used the plan and hit similar goals.
* It utilizes all of the power iTrackBites has, including our recipes, food items, custom recipes/foods, and most importantly, our community.

### How
* iTrackBites has worked with our team to create the first set of featured meal plans
* The community is encouraged to create their own to use for themselves, but also to share with others.
* Collaboration is key, and we believe nothing is static forever. Meals and their ingredients change over time, over seasons, and for good reason. That’s why we have comments built right in.
* Sharing meals through the community or any other apps external to iTrackBites is also easy.
* Custom recipes/foods can also be included, for a full customization
* We make it easy to track each meal, by integrating meal plans right into the tracking features.

### How we built it
* Lots of brainstorming
* Data
* Talking to users
* Comparing with other offerings
* Looking at the uniqueness of our product and community to come up with the best solution
* Designing, iterating, prototyping, developing, testing
* Complexities of using meal plans, creating them, and modifying them. How do we keep track of all these different states?
* This is a polished beautiful way to use meal plans with the community, more to come.

### Meal Plan Features
1. Use Meal Plans — plan your future meals, easily track them
2. Modify — Modify any meal plan to your preference. You can modify the meal plan you’re using or one that you have created.
3. Create — create a brand new meal plan
4. Share — share your new meal plan that you created, or anyone else’s meal plan. Share via the community, or you can share it with any other apps like text, email, and more.
5. Communicate — each meal plan is it’s own community group. Conversations can happen within each meal plan, with people commenting in the comment tab
6. Grocery List — shop easily with our grocery list. It shows what you need. Aggregates similar ingredients across different recipes and foods.
7. Browsing, discovery — Browse Meal Plans will show featured meal plans, top meal plan creators, popular and new ones. Featured is what we control, but everything else is done through algorithms that picks the best.

## Details
### android
* Created meal plan: Missing pinned description on the `Comments` tab
* Create meal plan: Weight loss plan gets modified from the original value.
* Create Meal Plan: Missing Tap to add photo text/Default serving size field
* Featured Meal Plan Creators List - Android
* Created meal plan: Screen goes blank/No option to "Add days"
* Saved recipe from Community when added to the meal plan is duplicated.
* Meal Plan BITES: Inconsistency with BITES on changing weight loss plan.
* Meal Plan Search events are missing in Amplitude
* Add weight loss plan icon to meal plans - Android
* Meal Plans Top Creators - Android
* Add to Current Meal Plan: Meal type/Date/Serving size to have default values when coming from meal details screen
* Created Meal Plan: Use this plan is not available.
* Meal Plan Create: "Saving Meal Plan" takes forever
* Recipe image not updated on the meal detail snippet appropriately
* Recipe Screens from Meal Plans - Android
* Meal Plan Edit: User should not be allowed to edit if meal plan is not active.
* Add `DELETE` option to meal plan menu - Android
* Remove Day in Meal Plan Create/Edit Screen - Android
* Add CTA to edit meal plan on empty grocery list - Android
* Add `Track Meal` button in the meal details bottom sheet
* Meal Plan Menu Updates for new edit flow - Android
* Meal Detail Screen will no longer modifiable - Android
* Use this plan option still shows for currently active meal plan
* Add text to empty grocery list - Android
* Need explainer text for Default Serving Size on Meal Plan Creation screen
* Adding a Recipe does not work
* Adding food to a meal plan doesn't work and causes meal plan to go blank
* User Profile: Meal Plans category should show just the created meal plans
* Create Meal Plan: Couldn't follow meal plan error
* Duplicate meal plans are created under Profile
* Edit Weight Loss Plan for a Meal Plan - Android
* Meal Plans Search - Android
* New Create/Edit Screen - Android
* Create Meal Plan: BITES mismatch between details and search results screen
* `REMOVE LAST DAY` button - Android
* Recipes shared on the Community overlaps meal plan images.
* Top Meal Plan Creators: The look & feel of the list is not consistent with weight loss plans
* App Parameter Error
* Stop using this plan does not respond as expected
* Create Meal Plan: Grocery List not updated after adding recipe
* Meal Plan Comment: "Meal Plan not found" error message 
* Created meal plan: "Add to meal plan/Remove" should navigate to the meal plan details
* Scrolling the Create Meal Plan screen is very difficult
* Meal Plan Editing - Android
* Meal Plan Create/Edit Screen - Android
* Changing Weight Loss Plans: Missing Amplitude/Braze events
* Android: On the meal details menu, change the `CANCEL` button to `DONE`
* Android: + CREATE meal plan action on empty search does not work
* Android: Meal Details Screen giving error
* Android: Can't create/follow meal plan
* Android: Screen 2 of creation needs to be updated
* Android: When creating a meal plan from scratch, do not include serving size (default to 1)
* Edited meal plan: Started meal plan different from the one displayed under "Your Meal Plan" subtab
* Edited meal plan: "Use this Plan" option displays on each meal item
* Meal Plan Comments: Unable to view text box/no focus while posting comments
* Edited meal plan: No "Use this Plan" option after first edit
* Create Meal Plan: Food details shows "0" BITES for all the search results
* Add Food To Meal Plan - Android
* Created Meal Plan: Custom food is not added appropriately
* Create/Edit: Weight Loss Plans displayed as Flex/Plus/Classic
* Edit Meal Plan: Grocery List not updated after removing recipe from meal plan
* Free/Non-pro users are allowed to edit/delete meal plan
* Use this Plan: Navigating back shows blank "Meal Plans" screen
* Featured meal plan edit should not allow modifying title/description
### api
* Meal Plans - Added foods or recipes need serving sizes
* Add Monitoring for Nutritionix error codes
* Whisk Shopping List Research
* Meal Plan Search
* Meal plan API calls with custom foods GUID
* Add delete meal plan API endpoint
* Meal Plan New List
* Meal Plans - Adding custom recipe and foods
* Custom Food: Shows "0" BITES for existing food items with no macro information.
* Meal Plan Search: Results to show all available meal plans on selecting all weight loss plans
* Meal Plan Admin - filter for "official" meal plans
* User who created a meal plan now shouldn't fork it when using it
### ios
* Hide "Track Meal" button from meal detail snippet
* Deleting meal plan does nothing
* App Crash on tapping Create Meal Plan "+"
* Featured Meal Plan Creators List - iOS
* App Badge settings not saved appropriately
* Meal Plan Search: Keyboard not dismissed after tapping "Search"
* Remove Day in Meal Plan Create/Edit Screen - iOS
* Edit Weight Loss Plan for a Meal Plan - iOS
* Meal Plan Creator: Invite group shows "Bad request error"
* Edit Meal Plan Info dismisses the active meal plan
* Meal Plan Comment: Count not updated on the "Your Meal Plan" sub tab.
* Custom recipe: BITES mismatch on the meal details/recipe details
* Top Meal Plan Creator's list shows user created meal plans
* Created meal plan: Button displays with shadow like watermark
* Custom recipe: Ingredients added are duplicated twice after Save
* Meal Plans Search - iOS
* Edit Meal Plan: Save does not respond appropriately
* iOS: No Serving size when you're not using meal plan during creation/edit
* Meal Plan Search: Missing Amplitude/Braze events.
* Meal Plan Item Remove: `Incomplete item` warning message appears while trying to remove the food
* Meal Plan Buttons: To have consistent style across screens/To remove "Track Meal" option
* Meal Plan Edit: User should not be allowed to edit if meal plan is not active.
* Add `DELETE` option to meal plan menu - iOS
* Track food: Missing "Remove" from the food details screen
* Add weight loss plan icon to meal plans - iOS
* Edit Meal Plan Info: Modified fields are not saved on return
* Custom recipe without image displayed as blank space
* App Crash: Commenting to the post from user profile
* Meal Detail Screen will no longer modifiable - iOS
* Meal Plan Menu Updates for new edit flow - iOS
* New Create/Edit Screen - iOS
* Meal Plan Search: Screen does not display recently created meal plan
* Edit Meal Plan: No option to "Save"
* Meal Plan Search: Applying filters should dismiss the keyboard
* Stop using this plan does not respond as expected
* `REMOVE LAST DAY` button - iOS
* Add CTA to edit meal plan on empty grocery list - iOS
* Create/Edit: BITES mismatch for food items after saving the meal plan
* Food Details: Modifying a food item to Zero BITES is not reflected in meal plan
* Edit Meal Plan: Values not retrieved appropriately
* No option to edit empty meal plan after creation
* Food Details: Remove button displayed prior to adding it to the meal plan
* Edit Meal Plan: Displays blank white space while navigating back
* Create meal plan: Quick add/Create custom food/recipe shows only "Track".
* Adding Recipes: Serving size always defaulted to `2`
* Create Custom Recipe: Total BITES mismatch before/after saving
* iOS: Stop Using Meal Plan doesn't work
* iOS: Modifying meal plan doesn't save changes
* iOS: Create button should say `CREATE` not `SAVE`
* iOS: After adding food/recipe, keep the meal details open
* iOS: Meal Plan Title input field changes
* iOS: On the meal details menu, change the `CANCEL` button to `DONE`
* Your Meal Plan subtab: View state allows the user to edit
* Meal Plan Title: Difficult to find cursor spacing out
* Free/Non-pro users are allowed to edit/delete meal plan
* App Tracking Transparency
* Changing Weight Loss Plans: Missing Amplitude/Braze events 
* Search panel displays white space while navigating from screens.
* When switching weight loss plans with an active meal plan, ask to stop meal plan. - iOS
