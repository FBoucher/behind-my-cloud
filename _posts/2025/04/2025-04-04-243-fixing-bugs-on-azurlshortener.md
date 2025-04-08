---
layout: post
title: "Fixing bugs on AzUrlShortener (stream 243)"
featured-image: https://img.youtube.com/vi/G0ZYBYXOPQ0/hqdefault.jpg
date: 2025-04-04 06:30 -0500
categories: azurlshortener
---
## Summary

In this live stream, we work on bug fix for our URL shortener project. The issue: archived URLs were still functioning when accessed directly, bypassing the archive status entirely. This unexpected behavior undermined the purpose of archiving URLs and needed immediate attention. Our journey took us through the codebase to identify where the redirect functionality needed to be enhanced with a simple but critical check for the isArchived property. After successfully implementing the fix, we verified that archived URLs properly redirect to a default page instead of their original destination. We also began work on restoring the search functionality in the URL manager interface, implementing filtering capabilities using FluentUI Blazor components. Join us as we explore the code changes and improvements that keep our URL shortener running smoothly for both personal use and Microsoft's adoption of the project for Azure Communication Services

📺 - Twitch archive - stream no.243

## Replay

{% include youtube.html id="G0ZYBYXOPQ0" %}

<br/><!--more-->

### Project

All the code for this project is available on GitHub: azurlshortener - https://github.com/FBoucher/azurlshortener

### TodDos

- [X] azd news
- [X] MCP SDK
- [x] fix archive url
- [ ] **Add filter to the grid**

### Raids

- [@tbdgamer](https://www.twitch.tv/tbdgamer) has raided you with a party of 13

### Game Results

- [@phrakberg](https://www.twitch.tv/phrakberg): 0
- [@stoney_eagle](https://www.twitch.tv/stoney_eagle): 0
- [@fboucheros](https://www.twitch.tv/fboucheros): 96.65
