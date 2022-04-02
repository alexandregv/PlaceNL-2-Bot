# PlaceNL Bot

The bot for PlaceNL! This bot automatically fetches [orders](https://github.com/PlaceNL/Orders) every few minutes, to prevent bots from clashing.

## Installation Instructions

Before you start, make sure your pixel wait time has expired!

1. Install the [Tampermonkey](https://www.tampermonkey.net/) browser extension.
2. Click on this link: [https://github.com/PlaceNL/Bot/raw/master/placenlbot.user.js](https://github.com/PlaceNL/Bot/raw/master/placenlbot.user.js). If all goes well, Tampermonkey should offer to install a user script. Click on **Install**.
3. Reload your **r/place** tab. If all has gone well, you will see "Get access token..." at the top right of your screen. The bot is now active, and will keep you informed of what it is doing via these notifications at the top right of your screen.

## Disadvantages of this bot

- When the bot places a pixel, it will look to yourself like you can still place a pixel, while the bot has already done this for you (and you are therefore in the 5 minute cooldown).
- The bot does not take into account an existing cooldown, and therefore assumes that when you open **r/place** you can immediately place a pixel. As a result, your first pixel may, in the worst case, waste 4 minutes and 59 seconds of time.
