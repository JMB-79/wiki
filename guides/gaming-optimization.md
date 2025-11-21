---
title: Gaming Optimisation Guide
description: Optimise your connection for the best gaming experience
category: Advanced
author: Olilo Team
lastUpdated: 21/11/2025
---

# Gaming Optimisation Guide

Get the competitive edge with these tips to optimise your Olilo connection for gaming.

## Why Fibre is Perfect for Gaming

Olilo's fibre connection offers:
- **Low latency:** Under 15ms to most game servers
- **Symmetrical speeds:** Fast uploads for streaming whilst gaming
- **Consistent performance:** No slowdowns during peak hours
- **High bandwidth:** Multiple gamers can play simultaneously

## Wired vs Wireless

### Always Use Wired for Competitive Gaming

Ethernet connections provide:
- Lower latency (5-10ms less than WiFi)
- More stable connection
- No interference issues
- Maximum speeds

### If You Must Use WiFi

- Use 5 GHz band only
- Stay close to router
- Use WiFi 6 (AX) if possible
- Close doors between you and router

## Router Configuration

### Enable Quality of Service (QoS)

Prioritise gaming traffic over other activities:

1. Log into your router settings
2. Find QoS or Traffic Prioritisation
3. Set gaming as highest priority
4. Add your gaming device's IP or MAC address
5. Save settings

### Port Forwarding

Some games require specific ports to be open:

1. Find required ports for your game (check game's support site)
2. Log into router settings
3. Navigate to Port Forwarding section
4. Add rules for your gaming device
5. Test connection in-game

**Common Gaming Ports:**
- PlayStation: TCP 80, 443, 3478-3480 / UDP 3478-3479
- Xbox: TCP 3074 / UDP 88, 500, 3074, 3544, 4500
- Steam: TCP 27015-27030, 27036-27037 / UDP 4380, 27000-27031, 27036
- Epic Games: TCP 80, 443, 5222, 5795-5847 / UDP 5222, 5795-5847

### UPnP (Universal Plug and Play)

Enable UPnP for automatic port configuration:
- Easier than manual port forwarding
- Works with most games
- Enable in router settings

## Optimise Your Gaming Device

### PC Gamers

1. **Update network drivers**
   - Visit manufacturer's website
   - Download latest drivers
   - Restart after installing

2. **Close background applications**
   - Steam downloads
   - Windows updates
   - Cloud sync services
   - Browser tabs

3. **Disable Windows Game Bar** (if causing issues)
   - Settings > Gaming > Game Bar
   - Toggle off

4. **Use Game Mode**
   - Settings > Gaming > Game Mode
   - Toggle on for better performance

### Console Gamers

1. **Use wired connection**
   - Connect ethernet cable to console
   - Disable WiFi in console settings

2. **Set DNS servers**
   - Use Cloudflare or Google DNS
   - Can reduce lookup times

3. **Close other apps**
   - Streaming apps
   - Downloads
   - Background games

## Network Settings

### Choose the Right DNS

DNS affects how quickly you connect to game servers:

**CloudFlare DNS (Recommended):**
- Primary: 1.1.1.1
- Secondary: 1.0.0.1

**Google DNS:**
- Primary: 8.8.8.8
- Secondary: 8.8.4.4

**How to Change DNS:**

**On PC:**
1. Network Settings > Change Adapter Options
2. Right-click your connection > Properties
3. Select IPv4 > Properties
4. Enter DNS servers
5. Click OK

**On Console:**
1. Network Settings
2. Manual Setup
3. Enter DNS servers
4. Test connection

### Disable IPv6 (If Causing Issues)

Some games have IPv6 compatibility issues:
- Disable in network adapter settings
- Test if gaming improves

## Reduce Latency

### What is Latency?

Latency (ping) is the time for data to travel to the game server and back:
- Under 20ms: Excellent
- 20-50ms: Good
- 50-100ms: Playable
- Over 100ms: Noticeable lag

### Tips to Reduce Latency

1. **Use wired connection:** Saves 5-10ms
2. **Close bandwidth-heavy apps:** Stop downloads, streaming
3. **Choose nearby servers:** Select servers in your region
4. **Upgrade router:** Old routers add latency
5. **Check for interference:** Other devices can cause issues

## Bandwidth Management

### How Much Speed Do You Need?

Gaming doesn't require huge bandwidth:
- Most games: 3-6 Mbps download
- Streaming whilst gaming: Add 5-10 Mbps
- 4K streaming whilst gaming: Add 25 Mbps

**The real key is latency, not speed.**

### Multiple Gamers in Your Home

If several people game simultaneously:
- 100 Mbps: 2-3 gamers
- 500 Mbps: 4-6 gamers
- 1000 Mbps: 6+ gamers plus streaming

Use QoS to ensure fair bandwidth distribution.

## Streaming Whilst Gaming

### Upload Speed Matters

Olilo's symmetrical speeds are perfect for streaming:

**Twitch/YouTube Streaming Requirements:**
- 720p 30fps: 3-4 Mbps upload
- 1080p 30fps: 4-6 Mbps upload
- 1080p 60fps: 6-8 Mbps upload
- 4K 60fps: 20-25 Mbps upload

### Optimise Your Stream

1. **Use hardware encoding:** NVENC (Nvidia) or AMF (AMD)
2. **Set appropriate bitrate:** Don't exceed 80% of upload speed
3. **Use wired connection:** Critical for stable streaming
4. **Enable QoS:** Prioritise gaming over streaming if needed

## Troubleshooting Gaming Issues

### High Ping/Latency

1. Test ping to game servers
2. Run speed test at speedtest.olilo.co.uk
3. Check for background downloads
4. Restart router and gaming device
5. Switch to wired connection

### Packet Loss

Symptoms: Rubber-banding, teleporting, disconnects

**Solutions:**
1. Check all cable connections
2. Replace old ethernet cables
3. Update router firmware
4. Contact support if persistent

### Disconnections

1. Check router logs for errors
2. Verify ONT lights are stable
3. Test with different ethernet cable
4. Disable power-saving features on network adapter

### NAT Type Issues

**NAT Types:**
- Open (Type 1): Best for gaming
- Moderate (Type 2): Good for most games
- Strict (Type 3): May have connection issues

**Fix Strict NAT:**
1. Enable UPnP in router
2. Set up port forwarding
3. Put gaming device in DMZ (less secure)

## Advanced Tips

### Static IP for Gaming Device

Assign a static IP to your gaming device:
1. Prevents IP changes
2. Makes port forwarding reliable
3. Configure in router's DHCP settings

### Upgrade Your Ethernet Cable

Use Cat6 or Cat6a cables:
- Better shielding
- Less interference
- Supports higher speeds

### Gaming Router Features

Consider a gaming router with:
- Advanced QoS
- Gaming-specific optimisations
- Better processors
- More RAM for multiple devices

## Test Your Setup

### Measure Your Performance

1. **Ping test:** ping google.com in command prompt
2. **Speed test:** speedtest.olilo.co.uk
3. **In-game ping:** Check game's network stats
4. **Packet loss test:** Use pingplotter.com

### Benchmark Before and After

Test before making changes:
- Record ping times
- Note any lag or issues
- Test at different times of day

Make one change at a time and retest.

## Still Having Issues?

Contact our gaming support specialists:

- **Email:** support@olilo.co.uk
- **Live Chat:** Available on our website
- **Discord:** discord.gg/olilo

Mention you're a gamer for priority support!

Game on with Olilo! 🎮