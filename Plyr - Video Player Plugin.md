
title: Plyr - Video Player Plugin
slug: 4qP3-plyr-video-player-plugin
description: Learn documentation about Plyr - Video Player Plugin from Zeroqode
createdAt: Mon Mar 07 2022 13:56:20 GMT+0000 (Coordinated Universal Time)
updatedAt: Thu May 05 2022 07:05:42 GMT+0000 (Coordinated Universal Time)
---

:::hint
Link to plugin page: <https://zeroqode.com/plugin/plyr---video-player-plugin-1585752713801x567609432761491140>​
:::

# Introduction

Zeroqode Video Player Plugin Plyr's simple, lightweight, accessible and customizable library with HTML5, YouTube, and Vimeo media player that supports [modern](https://github.com/sampotts/plyr#browser-support) browsers.&#x20;

This video player comes with a range of Events, Actions and States to work with out of the box.

# Plugin Element proprieties&#x20;

The plugin comes with 3 visual elements which can be used for video playback by configuring them accordingly .

### Bubble Video

![](https://archbee-image-uploads.s3.amazonaws.com/P8ugLseqEajPeMKCggz_j/Ebpq-Sy7O1jfQykdKzHCz_image.png)

![](https://archbee-image-uploads.s3.amazonaws.com/P8ugLseqEajPeMKCggz_j/0Pg80yXyEaKkL6J_kcRL5_image.png)

Proprieties fields:

**Video source**
Static file : upload a single file via static file
Dynamic link: provide a dynamic link from db or list of files from database

**Poster**
Static file: upload an image via uploader to set as poster
Dynamic link: provide a dynamic link source to file from database

**Enable ads? (NEW!)**: True / false field which let's you enable or disable ads for your bubble video
**VI publisher ID (NEW!)**: Unique publisher identifier from <https://www.vi.ai/>&#x20;
**VAST URL (NEW!)**: Unique url tag with parameters for advertising &#x20;
**HLS source (NEW!)**: Used for HLS Streaming content (m3u8 playlist)&#x20;

## YouTube Video

![](https://archbee-image-uploads.s3.amazonaws.com/P8ugLseqEajPeMKCggz_j/zm2E69TnoPXzwcRv8YW-p_image.png)



Proprieties fields:

**Video ID**: provide an video ID from youtube (ex: EGn-QtxMEPI)
**Poster** : provide a poster image (either dynamic or static file)
Static file: upload an image via uploader to set as poster
Dynamic link: provide a dynamic link source to file from database
**Playsinline (NEW!)** :  Enable the playsinline attribute

## Vimeo Video

![](https://archbee-image-uploads.s3.amazonaws.com/P8ugLseqEajPeMKCggz_j/kAfZSf9bA69HKY_WAhoy2_image.png)



Proprieties fields:

**Video ID**: provide an video ID from vimeo (ex: 480825325)
**Poster **: provide a poster image (either dynamic or static file)
Static file: upload an image via uploader to set as poster
Dynamic link: provide a dynamic link source to file from database

# Installation and Setup

### Plugin installation and setup

All you need to do is to install the plugin, drag one of three visual elements of the plugin onto the page, give it a source and you're ready to go.

Once one of the elements is placed on the page, the user immediately gets access to all of the states and events, also actions that control the element itself.

## Setting up VAST and vi.ai profiles

### For creating a VAST Tag URL you can use:

1.  **Google AdManager Account**
    If you use Google Ad Manager (Google DFP), generating a VAST Tag is pretty straightforward.

    1\. Sign in to Google Ad Manager.

2.  Click Inventory and then Ad units.

3.  Locate and click your video ad unit.

4.  Click Generate tags.

5.  Complete the 3-step process and click Continue after each step (Tag type, Tag Options, and Tag Results)

6.  Click **done**.

**2. Third-Party Tools**
In addition, there are a couple of VAST tag generators (offered by the video players) in the market which can help you generate the template.

**If you already have a vast tag, then you can use it in the player. Just paste it into the dedicated field and check the enable ads checkbox**

![](https://archbee-image-uploads.s3.amazonaws.com/P8ugLseqEajPeMKCggz_j/F5dDR1m0yDdEuilImENcV_image.png)



**For enabling ads using vi.ai platform**

You must create a new account (or use the one created) at <https://www.vi.ai/> as an **advertiser**.&#x20;
Integrate your content into the VI platform per their instructions and get your publisher ID which can be used in the dedicated field and check the enable ads checkbox.

**Paste your publisher ID into the same field in the element properties and check the box.**

![](https://archbee-image-uploads.s3.amazonaws.com/P8ugLseqEajPeMKCggz_j/MB6A1_P9F5gwmqTckRrRa_image.png)

# Plugin Events, Actions and States

Each element of the plugin has the exposed states shown on the screens below. See their **Title **and **Type**

![](https://archbee-image-uploads.s3.amazonaws.com/P8ugLseqEajPeMKCggz_j/lr0yYA44GS8_HCYLfQyr3_image.png)

![](https://archbee-image-uploads.s3.amazonaws.com/P8ugLseqEajPeMKCggz_j/4qAslsKLs76fDObK0bR2M_image.png)



Each element of the plugin can trigger events shown on the screenshot below.

![](https://archbee-image-uploads.s3.amazonaws.com/P8ugLseqEajPeMKCggz_j/lIoc6pcN6fbeFqzuX0Ku__image.png)



And also each element of the plugin has a set of actions available for user.

![](https://archbee-image-uploads.s3.amazonaws.com/P8ugLseqEajPeMKCggz_j/L9aRF-sBAIcU4G9PLMwfr_image.png)

# Changelogs

### Update: 27/11/2020 -

*   Added the ability to display ads to the bubble video player element from the vi.ai platform and from the VAST URL.&#x20;

*   Fixed bugs with elements size

### Update: 18/12/2020 -

*   Added new ability to add the HLS streaming videos for 'Bubble video' plugin element

### Update: 28/04/2021 -&#x20;

*   Fixed display issues

### Update: 24/05/2021

*   Added new option to stretch player to the parent group

![](https://archbee-image-uploads.s3.amazonaws.com/P8ugLseqEajPeMKCggz_j/4g9076EtLZwHJ4E1R9kRv_image.png)



### Update: 29/08/2021 - Version: 1.15.0

*   Added the ability to customize control bar color​​



![](https://archbee-image-uploads.s3.amazonaws.com/P8ugLseqEajPeMKCggz_j/QlpeWfvUERymS6BZ_FKSQ_image.png)

![](https://archbee-image-uploads.s3.amazonaws.com/P8ugLseqEajPeMKCggz_j/jIaCU7osjpVu-OF0_qhlv_image.png)

### Update: 28/09/2021 - Version: 1.16.0

*   Added custom style settings for the control panel and the playsinline checkbox for iOS

![](https://archbee-image-uploads.s3.amazonaws.com/P8ugLseqEajPeMKCggz_j/nfgJnShIjhkPGVqZNrHPh_image.png)



### ​Update: 28/10/2021 - Version: 1.17.0

*   Added the ability to lock the screen in landscape mode&#x20;

### Update: 08/12/2021 - Version: 1.18.0

*   Minor fix

### Update: 20/12/2021 - Version: 1.19.0

*   Removed Element ID field

### Update: 08/04/2022 - Version: 1.20.0

*   Fixed display of video parameters on IOS.

When playsinline checkbox on the plugin video element is checked - the played video is displayed within the frame of the plugin video element, and plugin element states are not avalable.&#x20;

When playsinline checkbox is unchecked - the played video is displayed in fullscreen regime, and plugin element states are available.&#x20;

# Demo to preview the settings

:::hint
Bubble Editor: [https://bubble.io/page?type=page\&name=plyr\&id=zeroqode-demo-21\&tab=tabs-1 ](https://bubble.io/page?type=page\&name=plyr\&id=zeroqode-demo-21\&tab=tabs-1)​
:::

:::hint
Live Demo: <https://zeroqode-demo-21.bubbleapps.io/plyr>
:::

