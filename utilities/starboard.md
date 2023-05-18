---
description: A Fun and Customizable Hub for Memorable Messages.
cover: >-
  https://images.unsplash.com/photo-1516571748831-5d81767b788d?crop=entropy&cs=srgb&fm=jpg&ixid=M3wxOTcwMjR8MHwxfHNlYXJjaHw5fHxzdGFyc3xlbnwwfHx8fDE2ODQyNDM2ODN8MA&ixlib=rb-4.0.3&q=85
coverY: 0
---

# ⭐ Starboard

{% hint style="warning" %}
Require bot permissions in the starboard channel:\
`ViewChannel`, `SendMessages`, `EmbedLinks`
{% endhint %}

### Configure

1. Install Waya on your server by going to [get.waya.one](https://get.waya.one).
2. Run the `/config` command and go to the **Starboard** tab.
3. Enable the module and set a _#starboard_ channel. ([Need help?](https://lunish.nl/support))
4. Configure anything as you want, when you're unsure what something does, read below.
5. 🎉 Done! _Try it out by reacting to any message with X emote._

{% embed url="https://medium.com/@wayabot/discord-starboard-with-waya-a-fun-and-customizable-hub-for-memorable-messages-94029e9ea00" %}

<figure><img src="../.gitbook/assets/image (2) (1).png" alt=""><figcaption><p>Starboard example inside of our server.</p></figcaption></figure>

### Config Options

Please note that the buttons in Waya **always** display the action they perform upon clicking, rather than reflecting the current state.

#### 🗨️ Edit Channel

Modify the destination channel for starred messages.\


#### ⭐ Change Emoji

Select a new emote required for reacting. This can be any default Discord emote or a custom emote **from the same server**.\


#### 🎨 Change Color

Customize the embed's color (left border) for messages in the starboard channel. Please get a valid hex color code from sites such as [https://htmlcolorcodes.com/color-picker/](https://htmlcolorcodes.com/color-picker/), include the `#` in the message, for example `#ffffff`.\


#### 🔢 Change Count

Adjust the number of reactions needed with the chosen emote to showcase a message on the starboard channel.\


#### 🧑‍🦰 Disable/Enable Self Reaction

Determine whether message authors can star their own messages. When disallowed, the author's reaction will be removed.\


#### 🔞 Disable/Enable NSFW

Specify whether Waya should include messages from NSFW-marked channels in the starboard.

![](<../.gitbook/assets/image (5) (1).png>)\


#### 🤖 Enable/Disable Bots

Determine whether messages from bots can be displayed on the starboard.\


#### 📝 Show/Hide replied to

Choose whether the replied message should be visible within the starboard or not.

![](<../.gitbook/assets/image (8) (1) (1).png>)![](<../.gitbook/assets/image (6) (1).png>)\


#### 🖊️ Allow/Disallow Edits

If allowed, messages that are edited will also be updated in the starboard.

{% hint style="warning" %}
This feature can be abused if users edit their messages to display different content once it's on the starboard.
{% endhint %}

#### 📃 Enable/Disable Logging

Coming soon (description pending).

#### ❌ Edit Blacklisted Roles

Specify roles that are restricted from starring other people's messages and prevent their own messages from appearing on the starboard.\


#### 🗑️ Enable/Disable \<X Reactions

If enabled, Waya will remove messages from the starboard channel that no longer meet the required star count.

{% hint style="warning" %}
This could be prone to spamming if individuals repeatedly react and un-react to a message.
{% endhint %}

#### 😍 Display Type

Choose a style how the user should get displayed:

* Tag: `Coffee Girl#8888` (soon to be `@coffee_girl`)
* Username: `Coffee Girl`
* Nickname: `Luna`
* Guild Profile: `Luna` (with per guild avatar as icon)

![](<../.gitbook/assets/image (2).png>)

### Conclusion

In conclusion, Waya's Starboard feature offers a powerful and dynamic platform for highlighting exceptional messages within your Discord community. With its extensive customization options, including channel selection, emoji customization, and color preferences, you have full control over the visual appeal of your starboard. The ability to manage bot messages, hide replied-to messages, and control edits ensures a seamless and curated experience for your server members. Additionally, the flexibility to set blacklisted roles and enable or disable reactions maintains the integrity and quality of your starboard content. With Waya's Starboard, you can create a thriving and engaging community where outstanding messages are celebrated and appreciated.

### Video Tutorial

{% embed url="https://www.youtube.com/watch?v=lwMmGjgT_e0" %}
Watch how to setup the starboard!
{% endembed %}
