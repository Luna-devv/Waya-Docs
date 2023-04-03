---
description: User messages, voice and invite leaderboards, made easy.
cover: >-
  https://images.unsplash.com/photo-1549880181-56a44cf4a9a5?crop=entropy&cs=srgb&fm=jpg&ixid=MnwxOTcwMjR8MHwxfHNlYXJjaHw4fHxtb3VudGFpbnxlbnwwfHx8fDE2Nzk5OTQ2MTA&ixlib=rb-4.0.3&q=85
coverY: 190
---

# 👀 Leaderboards

{% hint style="warning" %}
J**ust added?** The bot starts tracking statistics as soon as it's invited to your server!
{% endhint %}

### Configure

1. Install Waya on your server by going to [get.waya.one](https://get.waya.one).
2. Type the `/leaderboards` or `/prompt leaderboards` command.
3. Set the config how you everything want. ([Need help?](https://lunish.nl/support))
4. Send the command.
5. 🎉 Done!&#x20;

<figure><img src="../.gitbook/assets/image (10).png" alt=""><figcaption><p>Waya message leaderboard</p></figcaption></figure>

### Commands

There are 2 different commands to show a leaderboard.

* `/leaderboard <type> <..>` Shows a static leaderboard as a command reply.
* `/prompt leaderboard <type> <...........>` Shows an updating leaderboard, updates all 8 minutes.

There are 3 different leaderboard types (which are pretty obvious) that show different data.

* **Messages**: Shows how many messages a user has sent.
* **Voice**: Shows how long a user was in voice. _(doesn't count if ur alone sry introverts)_
* **Invites:** Shows how many members a user has invited.

{% hint style="info" %}
**Messages:** Bot is required to have \`ViewChannel\` permissions in every channel.

**Voice:** Bot is required to have \`ViewChannel\` permissions in every voice channel.

**Invites:** Bot is required to have \`ManageServer\`.
{% endhint %}

### Features in words

With 🗨️ **Waya's** [**message tracking**](#user-content-fn-1)[^1]**,** the bot records all messages sent by a user, providing you with a clear understanding of their activity levels. Additionally, Waya also offers an 🔗 **invite leaderboard**, which displays the number of users a member has invited to the server. Last but not least, Waya 🔊 **tracks the time your users where connected to a voice chat**.

The leaderboard always shows the top 10 members in the category of your server. There are **two types of leaderboards available - static and updating**. The static leaderboard shows only the current stats and your own position, while the updating leaderboard updates in intervals of up to 8 minutes (or less/more often) to reflect the most recent data.

![](../.gitbook/assets/image.png)

Additionally, Waya's leaderboard feature **allows you to configure a reward role** for the top 3 most active users in message count and voice time. You can set this up in the **/config > miscs > leaderboards > roles** section of the bot.

![](<../.gitbook/assets/image (12).png>)

### Static leaderboard

The static leaderboard offers options such as user display style (`id`/`username`/`tag`/`nickname`/`mention`) and visibility (`public`/`hidden`), allowing you to customize the command to suit your server's needs. You can choose whether only you or everyone in the server can see the leaderboard.

### Updating leaderboard

The updating leaderboard provides further customization options, including user display style (`id`/`username`/`tag`/`nickname`/`mention`), full custom embed, and the ability to quote the leaderboard data itself (`>` symbol). Additionally, **you can choose the style of the rank, number, and/or user**, with options such as normal, bold, italic, and code available.

### Pace command

The `/pace` command calculates your average messages per day and **predicts your next milestone based on your past analytics**. This is a very neat tool to fight against your friends in server activity.

<figure><img src="../.gitbook/assets/image (11).png" alt=""><figcaption><p>/pace command</p></figcaption></figure>

### Conclusion

In conclusion, Waya's leaderboard feature is an incredibly powerful and engaging tool for any Discord server. With its comprehensive tracking and customization options, it offers more than many paid alternatives on the market. From message tracking to invite leaderboards to voice time tracking, the leaderboard feature helps keep your server active and engaging for all members. And the best part? It's completely free. Give your server the boost it deserves with Waya's leaderboard feature.

[^1]: However, the content of the messages is not recorded for privacy reasons.&#x20;
