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

<figure><img src="../.gitbook/assets/image (14).png" alt=""><figcaption><p>Waya message leaderboard</p></figcaption></figure>

{% content-ref url="../slash-commands/pace.md" %}
[pace.md](../slash-commands/pace.md)
{% endcontent-ref %}

### Commands

There are 2 different commands to show a leaderboard.

* `/leaderboard <type> <..>` Shows a static leaderboard as a command reply.
* `/prompt leaderboard <type> <...........>` Shows an updating leaderboard, updates all 20 minutes.

### Features in words

With 🗨️ **message tracking,** the bot records all messages sent by a user, providing you with a clear understanding of their activity levels. Additionally, Waya also offers an 🔗 **invite leaderboard**, which displays the number of users a member has invited to the server. Last but not least, Waya 🔊 **tracks the time your users where connected to a voice chat**.

{% tabs %}
{% tab title="Messages" %}
Shows how many messages a user has sent since they/the bot joined the server.

<figure><img src="../.gitbook/assets/image (4).png" alt=""><figcaption><p>/leaderboard for member message count</p></figcaption></figure>

{% hint style="danger" %}
Bot is required to have `ViewChannel` permissions in every channel.
{% endhint %}
{% endtab %}

{% tab title="Voice" %}
Shows how long a user was in any voice channel with anyone else since they/the bot joined the server.

<figure><img src="../.gitbook/assets/image (19).png" alt=""><figcaption><p>/leaderboard for member voice time</p></figcaption></figure>

{% hint style="danger" %}
Bot is required to have `ViewChannel` permissions in every voice channel.
{% endhint %}
{% endtab %}

{% tab title="Invites" %}
Shows the amount of members the user has invited since they/the bot joined the server.

<figure><img src="../.gitbook/assets/image (17).png" alt=""><figcaption><p>/leaderboard for member invite count</p></figcaption></figure>

{% hint style="danger" %}
Bot is required to have `ManageGuild` permissions.
{% endhint %}
{% endtab %}
{% endtabs %}

Additionally, Waya's leaderboard feature **allows you to configure a reward role** for the top 3 most active users in message count and voice time. You can set this up in the **/config > miscs > leaderboards > roles** section of the bot.

<div align="left">

<figure><img src="../.gitbook/assets/image (12) (1) (1).png" alt="" width="375"><figcaption></figcaption></figure>

</div>



### Config Options

#### 😍 Display Type

Choose a style how the user should get displayed:

* User mention: @`Coffee Girl` (clickable)
* Username: `Coffee Girl`
* Nickname: `Luna`
* Tag: `Coffee Girl#8888` (soon to be `@coffee_girl`)
* Id: `821472922140803112`\


#### 🔥 Title

The title of the leaderboard embed.\
![](<../.gitbook/assets/image (10).png>)

#### 🖼️ Thumbnail

The small image on the right site of the embed. (1 : 1 ratio)\
![](<../.gitbook/assets/image (22).png>)

#### 🖼️ Image

The big image bellows the top listed users.\
![](<../.gitbook/assets/image (8).png>)

#### 🤏 Footer

Small text on the very bottom of the embed.\
![](<../.gitbook/assets/image (3).png>)

#### 🎨 Color

Who would have guessed, the color on the left side of the embed.\
<img src="../.gitbook/assets/image (13).png" alt="" data-size="original">

#### ✨ Emote

The Emote used between the data and the user. You can use any default discord Emoji, most other Emojis and custom Emotes **from the same guild**.\
![](<../.gitbook/assets/image (21).png>)

#### 💬 Quote

Chose if you want that intended quote thing (`>`) on the embed.\
![](<../.gitbook/assets/image (15).png>)

#### 🔢 Rank / Number / User

Chose the format you want to use for those texts inside of the embed.

* Bold (**example**)
* Italic (_example_)
* Underline (example[^1])
* Code (`example`)
* None (example)

### Conclusion

In conclusion, Waya's leaderboard feature is an incredibly powerful and engaging tool for any Discord server. With its comprehensive tracking and customization options, it offers more than many paid alternatives on the market. From message tracking to invite leaderboards to voice time tracking, the leaderboard feature helps keep your server active and engaging for all members. And the best part? It's completely free. Give your server the boost it deserves with Waya's leaderboard feature.

[^1]: 
