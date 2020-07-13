---
layout:     post
title:      Fixing Maxed out manual allowances and CCPA
date:       2020-07-15 19:15:33
categories: info
---

v6.8.13

## Overview
There are alot of behind the scenes updates with this release that will be
ramping up for a few really exciting features coming soon. The biggest fix will
be for Keto Plans, where calories were maxing out at '600'. They are now no
longer maxxing out.

We are also continuing to be CCPA Compliant (California Consumer Policy Act),
and will be rolling out more and more features to ensure that we continually
adhere to what is required. There are a lot of backend changes that allow this
to happen, and users will not be affected in their use of the app.

Additionally, we have updated about a hundred or more PocketGuide bite counts so
that they are up to date, accurate, and what our community expects.

## Details
### android
* AppsFlyer SDK Update + CCPA -- Android
* Keto Plan - Total calories maxed out to '600' for manual allowances.
* Calculator Rounding - calculators now round accurately and are the same across
  all platforms
### ios
* Update Apptentive SDK 5.2.12 to avoid iOS 14 security warnings.
* AppsFlyer SDK Update + CCPA
* Calculator Rounding - calculators now round accurately and are the same across
  all platforms
### api
* Updating PocketGuide values for all search results. They should be very
  accurate now on all platforms (Android/iOS apps).
