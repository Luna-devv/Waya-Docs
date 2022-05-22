# Member filtering

Whith this method, you can filter out member where their account is younger than X days. <br />
You can choose between 4 diffrent actions, member **Ban**, **Kick**, **Timeout** until it reachers X days or simply **Assign Role**.

<img src='https://cdn.waya.one/r/1653237638.png' style='height: 16rem; border-radius: 0.4rem' />

## Permissions
In order you can follow this guide, you need the `MANAGE_GUILD` permissions in the guild. <br />
In the current channel you will need `VIEW_CHANNEL`, `SEND_MESSAGES` and `USE_APPLICATION_COMMANDS`.

It depends what permissions the bot needs on what punishment you select:
**Ban:** `BAN_MEMBERS`.
**Kick:** `KICK_MEMBERS`.
**Kick:** `KICK_MEMBERS`.
**Timeout:** `MODERATE_MEMBERS`.
**Assign Role:** `MANAGE_ROLES`.

!!! warning "Role hierarchy"

    Please make sure that the bot role is higher than the user roles! <br />
    However, feel free to join the [support server](https://discord.com/invite/rEsA5pZz4u).

## Configuration
Start by using [`/config`](/) and heading over to ^^Logging^^ => ^^Joins^^ => ^^Filter^^. <br />
At this point, you will be able to see the current configuration for Member Filtering.
You can change and modify anything with the buttons attached to the message.

### Setting up
1. Enable the module.
2. Set an age trigger.
3. Set a punishment.

### Limitations
The days variable can't be higher than 28 days and can't be lower than a day. <br />
You can only choose one punishment (and role) at the same time.