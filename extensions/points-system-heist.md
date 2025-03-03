---
title: Heists (by TerrierDarts)
description: With Heists you give chance for your viewers to join together in a raid in order to gain rewards in the chat.
published: true
date: 2023-05-05T20:43:32.841Z
tags: 
editor: markdown
dateCreated: 2022-11-07T15:27:23.684Z
---

# Import Code

```
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
```

# Installation

In Streamer.bot in select `Import` from the top left.
Copy the `Import Code` and paste it into the `Import String`.

Commands by default are disabled so `!heist-start` will need enabling for this to work.

Now using `!heist-start` should start an Heist!.

# Configuration

This has a high level of configuration so I will take you through the actions 1 by 1 explaining what each bit does.

Firstly just note that this can be triggered from a timed action you would just need to have the timed action trigger the `[Currency] - [Heist] - Start` Action. You can also edit the commands too if you wish.

### [Currency] - [Heist] - Start
The first thing to note here is you can add more heists if you wish however you will need to take care in the numbering system for the purpose of this explaination numbers will be defined as `X`.
|Argument|Purpose|
|--|--|
|`heistNameX`|This is the name of the Heist|
|`heistPotX`| This is the amount to be won.|
|`heistMaxEntX`|This is the max number allowed in to the heist.|
|`heistBaseSurvialX`|This a difficulty percentage. higher = harder|
|`heistBufferX`|This is the amount removed from the `hiestBaseSurvial` based on the number of people who join|
|`length`|How long the heist is open for|
|`trigger`| This is how people can join ( if you change commands this might need changing too)|
|`heistCost`| How many points it cost to join ( this can be 0)|
|`numOfHeists`| This is how many heists you have|
|`bot`|  This controls if the output to chat comes from the bot account|

### [Currency] - [Heist] - Join
|Argument| Purpose|
|--|--|
|`sharesBase`| This is the base amount of shares a user will get.|
|`sharesMOD`| This is additional shares for been a mod.|
|`sharesVIP`| This is additional shares for been a VIP|
|`sharesSUB`| This is additional shares for been a Sub|
|`surviveBase`| This is base survival rate the higher it is the better chance of survival|
|`surviveMOD`| This increases surival rate for been a mod|
|`surviveVIP`|This increases surival rate for been a VIP|
|`surviveSUB`|This increases surival rate for been a Sub|
|`bot`| This controls if the output to chat comes from the bot account|

### [Currency] - [Heist] - End
|Argument| Purpose|
|--|--|
|`winnersOnly`|This controls if only winners get posted to chat|
|`spamProtection`|This controls if winners are posted as 1 message each or as 1 long message|
|`bot`| This controls if the output to chat comes from the bot account|

Please take into account Twitch has a 500 character limit


# Contributors

 - [TerrierDarts](https://www.twitch.tv/TerrierDarts){.twitch}
 {.contributors}