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

## Configure

1. Install Waya on your server by going to [get.waya.one](https://get.waya.one).
2. Run the `/config` command.
3. Go to **Logging > Welcomer** and click **Enable**.
4. Click **Set Channel** and enter your welcoming channel.
5. Setup any options you like! ([Need help?](https://lunish.nl/support))
6. 🎉 Done! Try it out with `wa greet`

<figure><img src="https://c.lunish.nl/r/PLWnHt.png" alt="Example welcomer message of someone joining the server and Waya sending a nice welcomer message"><figcaption><p>Example welcome message</p></figcaption></figure>

## Config Options

Waya's welcome feature provides an excellent opportunity to make new members feel more welcome and appreciated. With its full customization options, you can create a personalized message that suits your server's tone and vibe.

### ✏️ Custom Message & Reactions

You can create a welcoming message with a **fully customizable message and embed**, making it easy to convey your server's culture and values to your new members. You can also add a few **reactions to the welcome message** and the users first message!\
![](<../../.gitbook/assets/image (12) (2).png>)

### 🏓 Join Pings

Waya also allows you to **ping your new members in up to 15 channels** if you have [Waya Enterprise](https://waya.one/enterprise), or up to 5 channels in the free plan.\
![](<../../.gitbook/assets/image (13) (1) (1).png>)

### 👀 Join Roles

This gives you the ability to **assign up to 10 roles** with [Waya Enterprise](https://waya.one/enterprise), or up to 5 roles in the free plan.\
![](<../../.gitbook/assets/image (11) (1).png>)

### 💬 Direct Message

If you want to **send a direct message to your new members**, Waya also allows you to do so with a fully custom message and embed.\
![](<../../.gitbook/assets/image (15) (1) (2).png>)

### 👋 Wave to say Hi

Waya supports the `Wave to say Hi!` button feature found in Discord's welcome messages. You can **customize the button's colors, label, and emote, and the response message and embed** to create a personalized and unique welcome experience. Alternatively, you can **add a random sticker** instead. You also have the option to **disable the ping** for the welcomed user.\
![](<../../.gitbook/assets/image (8) (1).png>)

### ♻️ Restore Roles/Nick after Rejoin

In addition, with Waya, you can **delete the join message after a set time**, **edit the message if the member leaves** and **re-assign all roles and nicknames when they rejoin** your server.\
![](<../../.gitbook/assets/image (7).png>)

### 🖼️ Welcome Image

You can create a visually captivating welcome image by customizing the background and text colors. Make a lasting impression on new members with a personalized and visually appealing welcome experience.

{% hint style="warning" %}
Custom background image: **1024x256px** (width, height) and must be `.png`, `.jpg` or `.jpeg`
{% endhint %}

Background images:

* Join: [imagerenderer.waya.one/static/grass.jpg](https://imagerenderer.waya.one/static/grass.jpg) (default)
* Join (left): [imagerenderer.waya.one/static/orange-grass.jpg](https://imagerenderer.waya.one/static/orange-grass.jpg) (default)
* Leave: [imagerenderer.waya.one/static/red-grass.jpg](https://imagerenderer.waya.one/static/red-grass.jpg) (default)
* Custom: [cdn.waya.one/welcome-bp.png](https://cdn.waya.one/welcome-bp.png) (example from below)

<figure><img src="../../.gitbook/assets/welcome (1).png" alt=""><figcaption><p>Fancy welcome image</p></figcaption></figure>



## Placeholders

### Joining User

<table><thead><tr><th width="171.33333333333331">Placeholder</th><th width="354">Example</th><th>Description</th></tr></thead><tbody><tr><td><code>user.mention</code></td><td>@Luna</td><td>User mention</td></tr><tr><td><code>user.id</code></td><td>821472922140803112</td><td>User id</td></tr><tr><td><code>user.tag</code></td><td>Coffee Girl#8888</td><td>User tag</td></tr><tr><td><code>user.name</code></td><td>Coffee Girl</td><td>Username</td></tr><tr><td><code>user.avatar</code></td><td><a href="https://cdn.discordapp.com/avatars/821472922140803112/4a0d2627b54af074656245c8c6f6b9fc.png?size=2048">https://cdn.discordapp.com/avatars/821472922140803112/4a0d2627b54af074656245c8c6f6b9fc.png</a></td><td>Avatar URL</td></tr><tr><td><code>user.discrim</code></td><td>8888</td><td>Discriminator (without #)</td></tr></tbody></table>

### Current Guild

<table><thead><tr><th width="220">Placeholder</th><th width="321.3333333333333">Example</th><th>Description</th></tr></thead><tbody><tr><td><code>guild.name</code></td><td>Someone's</td><td>Server name</td></tr><tr><td><code>guild.id</code></td><td>828676951023550495</td><td>Server id</td></tr><tr><td><code>guild.avatar</code></td><td><a href="https://cdn.discordapp.com/icons/828676951023550495/a_d05303b604aa28b9c13eca7b5e804349.gif?size=512">https://cdn.discordapp.com/icons/828676951023550495/a_d05303b604aa28b9c13eca7b5e804349.gif</a></td><td>Icon URL</td></tr><tr><td><code>guild.rules</code></td><td>&#x3C;#!883818033867542648></td><td>Rules channel mention</td></tr><tr><td><code>guild.memberCount</code></td><td>848</td><td>Member count</td></tr></tbody></table>

{% hint style="warning" %}
`guild.rules` will show null if community isn't setup in your server.
{% endhint %}

### Inviter

<table><thead><tr><th width="181">Placeholder</th><th width="306.3333333333333">Example</th><th>Description</th></tr></thead><tbody><tr><td><code>user.mention</code></td><td>@Luna</td><td>User mention</td></tr><tr><td><code>user.id</code></td><td>821472922140803112</td><td>User id</td></tr><tr><td><code>user.tag</code></td><td>Coffee Girl#8888</td><td>User tag</td></tr><tr><td><code>user.name</code></td><td>Coffee Girl</td><td>Username</td></tr><tr><td><code>user.avatar</code></td><td><a href="https://cdn.discordapp.com/avatars/821472922140803112/4a0d2627b54af074656245c8c6f6b9fc.png?size=2048">https://cdn.discordapp.com/avatars/821472922140803112/4a0d2627b54af074656245c8c6f6b9fc.png</a></td><td>Avatar URL</td></tr><tr><td><code>user.discrim</code></td><td>8888</td><td>Discriminator (without #)</td></tr><tr><td><code>inviter.code</code></td><td>yYd6YKHQZH</td><td>Invite code</td></tr><tr><td><code>inviter.count</code></td><td>259</td><td>Count of invited users</td></tr></tbody></table>

### Random Greets

There is a way to show a random greet every time a user joins just via `{random[english]}`. ![](<../../.gitbook/assets/image (13) (1) (2).png>)![](<../../.gitbook/assets/image (20).png>)

**Supported languages**

```
{random[english]}, {random[german]},
{random[spain]}, {random[french]},
{random[polish]}, {random[italian]},
{random[croatian]}, {random[ukrainian]},
{random[dutch]}, {random[swedish]},
{random[finish]}, {random[albanian]},
{random[turkish]}
```

#### **Supported types**

| Placeholder | Example          | Description  |
| ----------- | ---------------- | ------------ |
| mention     | @Luna            | User mention |
| tag         | Coffee Girl#8888 | User tag     |
| name        | Coffee Girl      | Username     |

Usage: `{random[english,username]}`. **⚠️ With no space!**

## Conclusion

In conclusion, Waya's welcome feature is a top-of-the-line tool that surpasses even many paid alternatives, making it an incredible value for Discord server owners and admins. With its customizable welcome message, role assignments, direct messaging, and even the ability to add a custom welcome card, Waya's welcome function offers unparalleled flexibility in creating a warm and personalized experience for new members. And the best part? Waya's welcome feature is entirely free, setting it apart from other bots that charge a fee for similar functionality. So why settle for less when you can have Waya's exceptional welcome feature at no cost?

## Video Tutorial

{% embed url="https://www.youtube.com/watch?v=vM1DO5sFCCE" %}
Watch a video tutorial
{% endembed %}
