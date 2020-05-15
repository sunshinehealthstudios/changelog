---
layout:     post
title:      Android-Price-and-Acknowledgements
date:       2020-05-15 13:32:01
categories: info
---

v6.8.9 - Android

## Overview
We have now implemented more safeguards for processing subscriptions in our
Android app so that more subscriptions are not accidentally refunded after not
getting a purchase acknowledgement. If a purchase is not fully acknowledged,
either through a problem with internet data connectivity or otherwise, our
Android app will now try again when it is able to, to ensure it can verify the
purchase through an acknowledgement step in the purchase handshake.

## Details

### Android
* Background worker added that will retry the acknowledgement step if neededj
  purchases
