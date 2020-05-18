---
layout:     post
title:      Forgot Password Enter
date:       2020-05-07 11:12:02
categories: info
---

v6.8.8a - Web

## Overview
On the forgot password screen, the form was not submitting when `enter` was
being used to complete the form. It would only work when the user clicked the
button. This fix will now allow the `enter` key to work correctly.

## Details

### Web
* The email form is now validating that the input is an email
* The email form field is now a required field, so it cannot be blank
* The email form can now be submitted with the `enter` key correctly
