---
description: Main settings for Invite Tracker.
---

# Main Settings

### General

| Command | Description |
| :--- | :--- |
| `-setprefix <prefix>` | Change the bot's prefix |
| `-setlang <language>` | Change the bot's language |
| `-config` | Display the bot's server configuration |
| `-syncinvites` | Synchronize current bot invites with the one in the Invites tab in your server settings |
| `-channelblacklist  <add/remove/list> [#channel]` | Add/remove/list a blacklist channel, messages in these channels are not going to be counted. |

## Announcement Channels

| Command | Description |
| :--- | :--- |
| `-configchannel  <join | leave> <#channel>` | Set the channel where join or leave messages will be sent |

## Announcement Messages

See the [Variables](https://docs.invite-tracker.com/invite-tracker/variables) for variables which will help you make the perfect message!

| Command | Description |
| :--- | :--- |
| `-configmessage <join | leave | joindm> <normal | vanity | bot | no-perm | unknown> <message>` | Set the join, leave or join DM message for each type |

{% hint style="warning" %}
If you want to define a **Join DM** message, make sure to specify `normal` for the message type.
{% endhint %}

{% hint style="info" %}
Normal, vanity, bot, no-perm, unknown are the way a new member joined your server, that mean you can display a different message depending on how a member joined.

`normal` - The new member joined with a normal invite and the bot is able to know by who he was invited.  
`vanity` - The new member joined through a vanity invite \(discord.gg/abc\).  
`bot` - The new member who joined is a bot.  
`no-perm` - The bot do not have the required permissions to track who invited the member, make sure to grant the right permissions to the bot, read the [Getting Started](https://docs.invite-tracker.com/#getting-started) section for further information.  
`unknown` - The bot is not able to determine by who the new member was invited, this is _rare case_.
{% endhint %}

## Announcement Status

| Command | Description |
| :--- | :--- |
|  `-configenable <join/leave/joindm> <True/False>` | Enable or disable the join, leave or join DM messages |

## Rewards Roles

| Command | Description |
| :--- | :--- |
| `-rewardroles add <@role> <message count>` | Add a reward role for messages. |
| `-rewardroles remove <@role> <message count>` | Remove a reward role for messages. |
| `-rewardsroles` | Display all off the existant rewards roles for messages. |

