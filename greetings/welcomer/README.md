---
description: Welcome new members to the community!
cover: >-
  https://images.unsplash.com/photo-1563089145-599997674d42?crop=entropy&cs=srgb&fm=jpg&ixid=MnwxOTcwMjR8MHwxfHNlYXJjaHw5fHxwdXJwbGV8ZW58MHx8fHwxNjc5Nzc5NzE0&ixlib=rb-4.0.3&q=85
coverY: -334
---

# 🌊 Welcomer

{% hint style="warning" %}
Require bot permissions in the channel:\
`ViewChannel`, `SendMessages`, `EmbedLinks`, `AttachFiles`
{% endhint %}

### Configure

1. Install Waya on your server by going to [get.waya.one](https://get.waya.one).
2. Run the `/config` command.
3. Go to **Logging > Welcomer** and click **Enable**.
4. Click **Set Channel** and enter your welcoming channel.
5. Setup any options you like! ([Need help?](https://lunish.nl/support))
6. 🎉 Done! Try it out with `wa greet`

<figure><img src="https://c.lunish.nl/r/PLWnHt.png" alt="Example welcomer message of someone joining the server and Waya sending a nice welcomer message"><figcaption><p>Example welcome message</p></figcaption></figure>

### Config Options

Waya's welcome feature provides an excellent opportunity to make new members feel more welcome and appreciated. With its full customization options, you can create a personalized message that suits your server's tone and vibe.

#### Custom Message & Reactions

You can create a welcoming message with a **fully customizable message and embed**, making it easy to convey your server's culture and values to your new members. You can also add a few **reactions to the welcome message** and the users first message!\
![](<../../.gitbook/assets/image (12).png>)

#### Join Pings

Waya also allows you to **ping your new members in up to 15 channels** if you have [Waya Enterprise](https://waya.one/enterprise), or up to 5 channels in the free plan.\
![](<../../.gitbook/assets/image (13) (1) (1).png>)

#### Join Roles

This gives you the ability to **assign up to 10 roles** with [Waya Enterprise](https://waya.one/enterprise), or up to 5 roles in the free plan.\
![](<../../.gitbook/assets/image (11).png>)

#### Direct Message

If you want to **send a direct message to your new members**, Waya also allows you to do so with a fully custom message and embed. \
![](<../../.gitbook/assets/image (15) (1).png>)

#### Wave to say Hi

Waya supports the `Wave to say Hi!` button feature found in Discord's welcome messages. You can **customize the button's colors, label, and emote, and the response message and embed** to create a personalized and unique welcome experience. Alternatively, you can **add a random sticker** instead. You also have the option to **disable the ping** for the welcomed user.\
![](<../../.gitbook/assets/image (8) (1).png>)

#### Restore Roles/Nick after Rejoin

In addition, with Waya, you can **delete the join message after a set time**, **edit the message if the member leaves** and **re-assign all roles and nicknames when they rejoin** your server.\
![](<../../.gitbook/assets/image (7).png>)

#### Welcome Image

You can create a visually captivating welcome image by customizing the background and text colors. Make a lasting impression on new members with a personalized and visually appealing welcome experience.\
![](../../.gitbook/assets/welcome.png)

### Placeholders

#### Joining User

| Placeholder     | Example                                                                                                                                                                                            | Description               |
| --------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------- |
| `user.mention`  | @Luna                                                                                                                                                                                              | User mention              |
| `user.id`       | 821472922140803112                                                                                                                                                                                 | User id                   |
| `user.tag`      | Coffee Girl#8888                                                                                                                                                                                   | User tag                  |
| `user.name`     | Coffee Girl                                                                                                                                                                                        | Username                  |
| `user.avatar`   | [https://cdn.discordapp.com/avatars/821472922140803112/4a0d2627b54af074656245c8c6f6b9fc.png](https://cdn.discordapp.com/avatars/821472922140803112/4a0d2627b54af074656245c8c6f6b9fc.png?size=2048) | Avatar URL                |
| `user.discrim`  | 8888                                                                                                                                                                                               | Discriminator (without #) |

#### Current Guild

| Placeholder          | Example                                                                                                                                                                                             | Description           |
| -------------------- | --------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | --------------------- |
| `guild.name`         | Someone's                                                                                                                                                                                           | Server name           |
| `guild.id`           | 828676951023550495                                                                                                                                                                                  | Server id             |
| `guild.avatar`       | [https://cdn.discordapp.com/icons/828676951023550495/a\_d05303b604aa28b9c13eca7b5e804349.gif](https://cdn.discordapp.com/icons/828676951023550495/a\_d05303b604aa28b9c13eca7b5e804349.gif?size=512) | Icon URL              |
| `guild.rules`        | <#!883818033867542648>                                                                                                                                                                              | Rules channel mention |
| `guild.memberCount`  | 848                                                                                                                                                                                                 | Member count          |

#### Inviter

| Placeholder      | Example                                                                                                                                                                                            | Description               |
| ---------------- | -------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- | ------------------------- |
| `user.mention`   | @Luna                                                                                                                                                                                              | User mention              |
| `user.id`        | 821472922140803112                                                                                                                                                                                 | User id                   |
| `user.tag`       | Coffee Girl#8888                                                                                                                                                                                   | User tag                  |
| `user.name`      | Coffee Girl                                                                                                                                                                                        | Username                  |
| `user.avatar`    | [https://cdn.discordapp.com/avatars/821472922140803112/4a0d2627b54af074656245c8c6f6b9fc.png](https://cdn.discordapp.com/avatars/821472922140803112/4a0d2627b54af074656245c8c6f6b9fc.png?size=2048) | Avatar URL                |
| `user.discrim`   | 8888                                                                                                                                                                                               | Discriminator (without #) |
| `inviter.code`   | yYd6YKHQZH                                                                                                                                                                                         | Invite code               |
| `inviter.count`  | 259                                                                                                                                                                                                | Count of invited users    |

#### Random Greets

There is a way to show a random greet every time a user joins just via `{random[english]}`. ![](<../../.gitbook/assets/image (13) (1).png>)![](<../../.gitbook/assets/image (20).png>)\
\
**Support Languages**

```
{random[english]}, {random[german]},
{random[spain]}, {random[french]},
{random[polish]}, {random[italian]},
{random[croatian]}, {random[ukrainian]},
{random[dutch]}, {random[swedish]},
{random[finish]}, {random[albanian]},
{random[turkish]}
```

**Supported Types**

| Placeholder | Example          | Description  |
| ----------- | ---------------- | ------------ |
| mention     | @Luna            | User mention |
| tag         | Coffee Girl#8888 | User tag     |
| name        | Coffee Girl      | Username     |

Usage: `{random[english,username]}`. **⚠️ With no space!**

### Conclusion

In conclusion, Waya's welcome feature is a top-of-the-line tool that surpasses even many paid alternatives, making it an incredible value for Discord server owners and admins. With its customizable welcome message, role assignments, direct messaging, and even the ability to add a custom welcome card, Waya's welcome function offers unparalleled flexibility in creating a warm and personalized experience for new members. And the best part? Waya's welcome feature is entirely free, setting it apart from other bots that charge a fee for similar functionality. So why settle for less when you can have Waya's exceptional welcome feature at no cost?

### Video Tutorial

{% embed url="https://www.youtube.com/watch?v=R7X8Kg1hL3k" %}
Watch a tutorial how it's being set up!
{% endembed %}
