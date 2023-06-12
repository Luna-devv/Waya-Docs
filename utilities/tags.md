---
description: Custom Commands made easy with no additional programming.
cover: ../.gitbook/assets/IMG_9366.jpg
coverY: -6
---

# 🪶 Tags

{% hint style="warning" %}
Required bot permissions in the command channel:\
`ViewChannel`, `SendMessages`, `EmbedLinks`
{% endhint %}

## Configure

1. Install Waya on your server by going to [get.waya.one](https://get.waya.one).
2. Run the `/tags create` command and choose if it should be a \*\*/\*\*command.
3. Set every text like you want it to be. ([Need help?](https://lunish.nl/support))
4. Saved your changes.
5. 🎉 Done! _Try it out with `wa tag <name>` or `/name`._

<figure><img src="../.gitbook/assets/image (4) (1).png" alt=""><figcaption><p>Custom command example</p></figcaption></figure>

## Commands

There are two main types of commands in Waya: those that allow you to manage your tags on the server, and those that enable you to execute your custom commands.

### Managing Tags

* `/tags create <tag-name> <?slash-command>` To create a new tag.
* `/tags edit <tag-name>` To edit an existing tag.
* `/tags delete <tag-name>` To delete a tag with it's \*\*/\*\*command.
* `/tags edit <tag-name>` To edit an existing tag.
* `/tags info <?tag-name>` To view tags analytics. (❤️ [Enterprise required](https://waya.one/enterprise))
* `/tags list` To list all tags in the server.
* `wa tags` To list all tags in the server.

{% hint style="info" %}
When listing tags, you will only see ones you have access to.
{% endhint %}

### Executing Tags

You have a variety of options to call your custom command in Waya:

* `wa tags <name>`
* `wa tag <name>`
* `wa cmd <name>`
* `wa cmds <name>`
* `wa command <name>`
* `wa commands <name>`
* `wa t <name>`
* `wa c <name>`

If you enable the Slash command **also**:\
Simply use `/<name>` (i.e.:`/<getting-ids>`) for even quicker access.

{% hint style="info" %}
The `<name>` placeholder can also be replaced with a tags alias, note that this does **not** work at Slash commands.
{% endhint %}

## Features in words

Tags are custom commands that you can set up for your Discord server, designed to help you streamline your communication and avoid repetitive tasks. With Waya, you can **create up to 30 custom commands** on the free plan, and an infinite number of commands with our [Enterprise plan](https://waya.one/enterprise).

You can set a fully customized message with a custom embed, using a variety of placeholders to create custom responses tailored to your server's needs. Additionally, you can set it up as a **ticket tag, which grants you access to ticket-specific data** in your custom command. You can also make your tag a **shiny slash command (/) ✨** for added convenience.\\

<figure><img src="../.gitbook/assets/image (3) (1) (2).png" alt=""><figcaption><p>Custom commands list</p></figcaption></figure>

Waya allows you to limit access to the command to users with specific permissions, including `Administrator`, `Manage Channels`, `Manage Guild`, `Manage Messages`, `Manage Nicknames`, `Manage Roles`, and `Manage Emojis & Stickers`, or `Manage Threads` permissions.

With [Waya Enterprise](https://waya.one/enterprise), you can also view analytics for individual tags or all tags, giving you valuable insights into how your server is using the tag feature.

<figure><img src="../.gitbook/assets/image (4) (2) (1).png" alt=""><figcaption><p>Tags info command (all tags)</p></figcaption></figure>

## Placeholders

### Command Executer

<table><thead><tr><th width="171.33333333333331">Placeholder</th><th width="353.0625">Example</th><th>Description</th></tr></thead><tbody><tr><td><code>user.mention</code></td><td>@Luna</td><td>User mention</td></tr><tr><td><code>user.id</code></td><td>821472922140803112</td><td>User id</td></tr><tr><td><code>user.tag</code></td><td>Coffee Girl#8888</td><td>User tag</td></tr><tr><td><code>user.name</code></td><td>Coffee Girl</td><td>Username</td></tr><tr><td><code>user.avatar</code></td><td><a href="https://cdn.discordapp.com/avatars/821472922140803112/4a0d2627b54af074656245c8c6f6b9fc.png?size=2048">https://cdn.discordapp.com/avatars/821472922140803112/4a0d2627b54af074656245c8c6f6b9fc.png</a></td><td>Avatar URL</td></tr><tr><td><code>user.discrim</code></td><td>8888</td><td>Discriminator (without #)</td></tr></tbody></table>

### Current Guild

<table><thead><tr><th width="220">Placeholder</th><th width="321.3333333333333">Example</th><th>Description</th></tr></thead><tbody><tr><td><code>guild.name</code></td><td>Someone's</td><td>Server name</td></tr><tr><td><code>guild.id</code></td><td>828676951023550495</td><td>Server id</td></tr><tr><td><code>guild.avatar</code></td><td><a href="https://cdn.discordapp.com/icons/828676951023550495/a_d05303b604aa28b9c13eca7b5e804349.gif?size=512">https://cdn.discordapp.com/icons/828676951023550495/a_d05303b604aa28b9c13eca7b5e804349.gif</a></td><td>Icon URL</td></tr><tr><td><code>guild.rules</code></td><td>&#x3C;#!883818033867542648></td><td>Rules channel mention</td></tr><tr><td><code>guild.memberCount</code></td><td>848</td><td>Member count</td></tr></tbody></table>

{% hint style="warning" %}
`guild.rules` will show null if community isn't setup in your server.
{% endhint %}

### Current Date

<table><thead><tr><th width="200.33333333333331">Placeholder</th><th>Example</th><th>Description</th></tr></thead><tbody><tr><td><code>{date.year}</code></td><td>2023</td><td>Current year in YYYY</td></tr><tr><td><code>{date.month}</code></td><td>05</td><td>Current month in MM</td></tr><tr><td><code>{date.day}</code></td><td>26</td><td>Current day as DD</td></tr></tbody></table>

<table><thead><tr><th width="199.33333333333331">Placeholder</th><th>Example</th><th>Description</th></tr></thead><tbody><tr><td><code>{date.unix.t}</code></td><td>16:20 / 4:20 PM</td><td>Short Time</td></tr><tr><td><code>{date.unix.T}</code></td><td>16:20:30 / 4:20:30 PM</td><td>Long Time</td></tr><tr><td><code>{date.unix.d}</code></td><td>20/04/2023</td><td>Short Date</td></tr><tr><td><code>{date.unix.D}</code></td><td>20 April 2023</td><td>Long Date</td></tr><tr><td><code>{date.unix.f}</code></td><td>20 April 2023 16:20</td><td>Short Date/Time</td></tr><tr><td><code>{date.unix.F}</code></td><td>Tuesday, 20 April 2023 16:20</td><td>Long Date/Time</td></tr><tr><td><code>{date.unix.R}</code></td><td>2 months ago</td><td>Relative Time</td></tr></tbody></table>

{% hint style="warning" %}
Date format will vary based on your timezone and language.
{% endhint %}

### Ticket

<table><thead><tr><th width="288">Placeholder</th><th width="209.33333333333331">Example</th><th>Description</th></tr></thead><tbody><tr><td><code>{ticket.name}</code></td><td>ticket-coffee-girl</td><td>Name of the ticket</td></tr><tr><td><code>{ticket.createdAt}</code></td><td>20 April 2023 16:20</td><td>Ticket creation date</td></tr><tr><td><code>{ticket.claimedBy}</code></td><td>@Coffee Girl</td><td>User mention of the staff</td></tr><tr><td><code>{ticket.channelId}</code></td><td>883817635081506886</td><td>Discord channel id</td></tr><tr><td><code>{ticket.creator.mention}</code></td><td>@Coffee Girl</td><td>Ticket creator mention</td></tr><tr><td><code>{ticket.creator.id}</code></td><td>821472922140803112</td><td>Ticket creator id</td></tr><tr><td><code>{ticket.creator.tag}</code></td><td>Coffee Girl#8888</td><td>Ticket creator tag</td></tr><tr><td><code>{ticket.creator.discrim}</code></td><td>8888</td><td>Ticket creator discriminator (without #)</td></tr></tbody></table>

{% hint style="warning" %}
`{ticket.claimedBy}` will be nothing if the ticket is not claimed.
{% endhint %}

## Conclusion

In conclusion, what sets Waya's tag feature apart is that it is entirely free, unlike other bots that charge a fee for similar functionality. This makes it an even more attractive option for server owners who want to enhance their server's communication and productivity without breaking the bank. So why settle for less when you can have Waya's top-notch tag feature at no cost?
