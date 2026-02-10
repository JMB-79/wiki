---
title: ASUS Router Setup Guide
description: Guide on how to setup an ASUS router for use with Olilo
category: Setup
author: Joe Baxter (Corrie)
lastUpdated: 02/10/2026
---

# Introduction

ASUS manufacture and supply a wide range of different router models, thankfully they all share similar software, but for the purposes of this guide the basic setup
will be the same. 
If your log in page looks like [this](images/asus-router-guide-loginpage.png), this guide is for you (Note: The colours may be different on your GUI depending on the model of router.)
This guide assumes that you have switched to Olilo from another ISP, and can log into the GUI through your browser.
If you don't know how to do this, please check [here](https://www.asus.com/uk/support/faq/1005263/), and come back here once you have logged in.

## Basic Setup

Once you're in, select ['WAN'](images/asus-router-guide-wan.png) on the left menu. Depending on which physical network you are using (Open Reach, CityFibre, or Freedom Fibre)
the following steps are slightly different. If you are not sure which physical network you are connected to, please refer to emails you have received from Olilo to confirm.

### Open Reach

- For 'WAN Connection Type', near the top of the [page](images/asus-router-OR-WAN1.png), select 'PPPoE'.
- Scroll down to ['Account Settings'](images/asus-router-OR-WAN2.png) and input the Username and Password supplied by Olilo.
- The rest of the settings on this page can be left as default.
- Click 'OK' at the bottom of the page to save the settings.

### CityFibre

- For WAN Connection Type, near the top of the [page](images/asus-router-CF-WAN2.png), select 'Automatic IP'.
- Click 'OK' at the bottom of the page to save the settings.
- Select ['LAN'](images/asus-router-LAN.png) on the left menu. 
- Select the ['IPTV'](images/asus-router-CF-IPTV1.png) tab at the top of the page.
- On this [page](images/asus-router-CF-IPTV2.png), for 'Select ISP Profile' select 'Manual Setting'. Three new sections will appear.
- On the 'Internet' line, type '911' next to 'VID'.
- The rest of the settings on this page can be left as default.
- Click Apply at the bottom of the page to save your settings.

### Freedom Fibre

- For WAN Connection Type, near the top of the [page](images/asus-router-CF-WAN2.png), select 'Automatic IP'.
- Click 'OK' at the bottom of the page to save the settings.

### IPv6

- To activate IPv6, select the 'IPv6' [page](images/asus-router-IPv6.png) option in the left menu.
- Select the 'Connection Type' as 'Native'.
- Click Apply at the bottom of the page to save your settings.

## Still Stuck?

Before contacting us:
1. Click on Network Map to see if the router states if it has connected, and if not if it provides an error message.
2. Try to restart the router.
3. Get in touch if it's still playing up

- **Discord:** discord.gg/olilo
