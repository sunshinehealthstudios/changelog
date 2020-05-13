---
layout:     post
title:      Google-Payment-Acknowledgement
date:       2020-05-13 14:50:11
categories: info
---

v6.8.8b - API

## Overview
This is a quick fix for processing payment acknowledgements for Google Play
subscription payments. Some users had their subscription payments refunded, and
PRO accounts then cancelled, due to an implementation not handling all Google
Play subspcription payment acknowledgements

## Details

### API
* New process for handling acknowledgements implemented
* A new pubsub setup for contacting Google Play Store about acknowledged
  purchases
* Internal admin for reviewing and monitoring this new payment process
