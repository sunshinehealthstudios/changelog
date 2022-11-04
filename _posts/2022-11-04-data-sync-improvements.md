---
layout:     post
title:      Data Sync Improvements
date:       2022-11-04 15:27:41
categories: info
---

v7.19.5

## Overview
This release introduces a brand new data synchronization system that greatly improves the speed of sending and receiving data from our servers. We have also included visuals within the app to show the progress, status, and controls to restart and fix any syncing problems that may occur.

## Details

### Android
* Fixed: Reverse pagination on historical tracking data so the latest history populates first.
* Fixed: Prioritize syncronization tasks so that more vital data is syncronized first and is available in the correct priorities of importance
* Added: New syncronization system that can detect errors, resume instead of restarting completely, and optimizes the sync process
* Added: UI/UX that notifies users of sync progress, more information on what sync is doing, and troubleshooting steps
