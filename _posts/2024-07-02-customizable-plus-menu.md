---
layout:     post
title:      Customizable Plus Menu
date:       2024-07-02 09:36:24
categories: info
---

v9.0

## Overview

We are excited to announce the introduction of a customizable plus menu for all
PRO users! The plus menu on our tab bar is the main access point for Healthi
actions, such as tracking food, activity, and more. We now allow users to add
their preferred shortcuts to the menu to access their favorite areas of the app
instantly. You can add shortcuts to browsing Restaurant food items directly, or
going to your community notifications from the menu as well. There are many
other customizations available as well.

We have also fixed a handful of other issues listed in detail below.

## Details

### iOS
* New: Customizable Plus Menu for PRO
* Fixed: iPad/iPhone - Unable to swipe across result tabs after scrolling
* Fixed: iPad - changing to portrait orientation resulted in a blank screen, but
  switching to landscape would fix the issue.
* Fixed: Edit food - for any fraction measurement serving size gets updated to 1
  by default
* Changed: Create food will no longer require calories as a mandatory field so
  it can support the previous "quick add" functionality.
* Fixed: Some users found their streaks would reset from the last update
* Fixed: Zero BITES toggle does not revert to the original BITE value when
  toggled off
* Changed: increased the size of the search tabs, located them above the search
  bar so that it has clear hierarchy of changing the search bar below, and added
animations to make it clear you can scroll horizontally
* Changed: Zero BITES tab now shows all Zero BITE foods at the start, instead of just
  featured. It does not include all variations of common foods, which can still
be searched for. Example: Apple is listed, but Fuji Apple is not on the list and
can be searched for.

### Android
* New: Customizable Plus Menu for PRO
* Fixed: More streak reset fixes
* Fixed: Macros do not update when changing serving size
* Fixed: Sometimes favorites are not saved
* Fixed: Keyboard would force cursor to the end of the search term even when
  trying to type somewhere not at the end. This was caused by a conflict with
the voice enabled keyboards.
