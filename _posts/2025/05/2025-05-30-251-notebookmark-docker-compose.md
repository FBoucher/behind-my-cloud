---
layout: post
title: "Deploying an .NET Aspire project locally with Docker Compose (stream 251)"
featured-image: https://img.youtube.com/vi/CZ1DzuAEAzM/hqdefault.jpg
date: 2025-05-30 06:30 -0500
categories: notebookmark
---
## Summary

Nice stream this week, live codeing on Note Bookmark. We added the required packages and Aspire CLI to generate the Docker Compose file and bicep files to be able to run the app locally while having the data in Azure. However the security used in this project: ServicePrincipal, was missing. When deployed fully in Azure the AZD manage that for us, but locally something was missing. In a future stream we will look at how to fix that.  

📺 - Twitch archive - stream no.251

## Replay

{% include youtube.html id="CZ1DzuAEAzM" %}

<br/><!--more-->

### Project

All the code for this project is available on GitHub: notebookmark - https://github.com/FBoucher/notebookmark

### Raids

- [@tbdgamer](https://www.twitch.tv/tbdgamer) has raided you with a party of 13

### Game Results

- [@groversaurus](https://www.twitch.tv/groversaurus): 0
- [@coppersbeard](https://www.twitch.tv/coppersbeard): 0
- [@codebymistakes](https://www.twitch.tv/codebymistakes): 0
- [@jeffs_hat_stand](https://www.twitch.tv/jeffs_hat_stand): 0
- [@lurkydev](https://www.twitch.tv/lurkydev): 0
- [@marcusvoicecoder](https://www.twitch.tv/marcusvoicecoder): 0
- [@gamlor](https://www.twitch.tv/gamlor): 0
- [@mcnets](https://www.twitch.tv/mcnets): 0
- [@fboucheros](https://www.twitch.tv/fboucheros): 16.51
- [@thecliptographer](https://www.twitch.tv/thecliptographer): 40.75
- [@jtsom](https://www.twitch.tv/jtsom): 49.49
- [@therealsurlybot](https://www.twitch.tv/therealsurlybot): 59.99
- [@undefined_process](https://www.twitch.tv/undefined_process): 64.88
- [@surlydev](https://www.twitch.tv/surlydev): 83.19
- [@fredda_the_cat](https://www.twitch.tv/fredda_the_cat): 83.63
- [@theunoriginaljerk](https://www.twitch.tv/theunoriginaljerk): 87.86

#### Statistics

- 🏆Best score: [@theunoriginaljerk](https://www.twitch.tv/theunoriginaljerk) with 87.86
- 😭Biggest loser: [@groversaurus](https://www.twitch.tv/groversaurus) with 6 drops and no high score
- 🍀Luckiest: [@theunoriginaljerk](https://www.twitch.tv/theunoriginaljerk) with best score 87.86 and only 6 drops
- 🎖️Super participant: [@groversaurus](https://www.twitch.tv/groversaurus) with 6 drops

### Notes/ References / Snippets

- Aspire 9.3 release: https://learn.microsoft.com/en-gb/dotnet/aspire/whats-new/dotnet-aspire-9.3
- aca nuget Aspire.Hosting.Azure.AppContainers
