---
description: >-
  The explanation for all the administration commands available for Invite
  Tracker.
---

# Administration

## Blacklisting

### Channelblacklist

Any message sent to any of the blacklisted channels will not be counted towards the user's total messages.   
You can only blacklist a maximum of 5 channels if you do not have premium enabled in your server.

| Command | Description |
| :--- | :--- |
| `-channelblacklist add <#channel>` | Adds the specified channel to the channel blacklist |
| `-channelblacklist remove <#channel>` | Removes the specified channel from the channel blacklist |
| `-channelblacklist list` | Lists all currently blacklisted channels |

### Userblacklist

Users that are user blacklisted will not have their **invites** counted towards their total amount of invites.  
You can only blacklist a maximum of 3 users if you do not have premium enabled in your server.

| Comand | Description |
| :--- | :--- |
| `-userblacklist add <@user>` | Adds the specified user to the user blacklist |
| `-userblacklist remove <@user>` | Removes the specified user from the user blacklist |
| `-userblacklist list` | Lists all currently blacklisted users |

## Invite Administration

| Command | Description |
| :--- | :--- |
| `-deleteinvite <code>` | Deletes the specified invite code |
| `-syncinvites [@user]` | Synchronizes the server's invites with everyone or a specific user |

## Pinned Leaderboard ![](../.gitbook/assets/premium.png) 

Pinned leaderboards will automatically update every 15 minutes.

| Command | Description |
| :--- | :--- |
| `-pinleaderboard messages <#channel>` | Pins the message leaderboard in a specified channel |
| `-pinleaderboard invites <#invites>` | Pins the invite leaderboard in a specified channel. |

## Roles

### Autorole

Automatically assign roles when a user joins the server.   
You can only have a maximum of 3 auto-roles if you do not have premium enabled in your server.

| Command | Description |
| :--- | :--- |
| `-autorole add <@role>` | Adds the specified role as an auto-role |
| `-autorole remove <@role>` | Removes a role as an auto-role |
| `-autorole list` | Lists all current auto-roles |

### Managementrole

Users with one of the management roles will be able to manage invites and messages for specified users.   
You can only have a maximum of 2 management roles if you do not have premium enabled in your server.

| Command | Description |
| :--- | :--- |
| `-managementrole add <@role>` | Adds the specified role as a management role |
| `-managementrole remove <@role>` | Removes the specified role as a management role |
| `-managementrole list` | Lists all current management roles |

### Rewardroles

Reward roles will be assigned to members when they send the specified number of messages.   
You can only have a maximum of 5 reward roles if you do not have premium enabled in your server.

**Remember**: All the roles you want Invite Tracker to assign has to be under its highest role. To claim your role after reaching the required amount of messages, you must do the command `-messages`.

| Description | Command |
| :--- | :--- |
| `-rewardroles add <@role> <messages>` | Adds the specified role as a reward role for the number of messages specified |
| `-rewardroles remove <@role>` | Removes the specified role as a reward role |
| `-rewardroles list` | Lists all current reward roles |

## Server Settings

| Description | Command |
| :--- | :--- |
| `-setprefix <prefix>` | Sets the bot's prefix. Every command has to start with either the prefix or with mentioning the bot. |
| `-permscheck` | Tells you if the bot is missing any essential permissions. |
| `-setlang` | Sets the primary language of the bot. Available languages are _English_, _French_, _German_, _Norwegian_ and _Russian_. |
| `-messagedelay <seconds>` | Sets the message counting cooldown. The bot will only count 1 message per x seconds. |
| ![](../.gitbook/assets/premium.png)`-fakedelay` `<days>` | Sets the number of days old an account has to be to not be counted as a fake invite |

{% hint style="info" %}
Note that not every single part of the bot is translated, such as the help commands.
{% endhint %}

