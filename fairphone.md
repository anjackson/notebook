---
title: fairphone
description: 
published: true
date: 2024-06-13T13:15:07.358Z
tags: 
editor: markdown
dateCreated: 2024-06-13T12:38:26.707Z
---

# Fairphone from iPhone

Large collection, so initial transfer failed.

## Photos

Don't even want iClouded photos as they are lower quality versions.

- Switch off iCloud photos and select 'remove from phone' when asked about whether to download to the phone.
- 10GB of photos remain, as were not messed with by iCloud.
- Manually checked recent photos were on the Mac, via iCloud.
- Connected iPhone to Mac...
- Used Photos, to check if anything appears to need importing.
- Tried to use `Image Capture` to delete all the photos. Didn't seem to work?! Even deleting one photo took ages and then failed.
- Restart iPhone...
- That seemed to help, _Image Capture_ reports 45,235 files (much larger than before, comparable to the whole collection's size) and deleting one worked. Trying to delete all...


## WhatsApp

WhatApp link new device as Companion first, so chats can transfer over, then switch SIM. Doesn't go back in time all that far, and doesn't include media.

## Podcasts

- https://typefully.com/NathanG/exporting-apple-podcast-subscriptions-GnNbnVa
- https://jiacai2050.github.io/podcasts-opml-exporter/

```bash
cp ~/Library/Containers/com.apple.podcasts/Data/Documents/PodcastsDB.plist ~/Downloads/
❯ ls -l ~/Downloads/Podcasts*
-rw-r--r--@ 1 anj  staff  17846 13 Jun 13:29 /Users/anj/Downloads/Podcasts-13_06_2024, 13 29 20.opml
-rw-r--r--@ 1 anj  staff  52451 13 Jun 13:29 /Users/anj/Downloads/PodcastsDB.plist
```

OPML file can be transferred using Google Drive.
