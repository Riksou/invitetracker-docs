---
description: The explanation for the giveaway command for Invite Tracker.
---

# Giveaways

## Giveaway Management

### Starting Giveaways

| Command | Description |
| :--- | :--- |
| `-giveaway start` | Starts a giveaway after asking you a few setup questions |
| `-giveaway start <duration> <winner amount> <prize>` | Starts a simple giveaway with no setup questions |

{% hint style="warning" %}
You can not configure Invite Tracker to send a dm to the winner\(s\), add roles to the winner\(s\), have requirements or give bonus entries to roles for giveaways when using the simple giveaway command.
{% endhint %}

### Stopping Giveaways

| Command | Description |
| :--- | :--- |
| `-giveaway end <message id>` | Ends the giveaway with the specified message ID |
| `-giveaway delete <message id>` | Deletes the giveaway with the specified message ID |

{% hint style="info" %}
When ending a giveaway it will choose winners. When deleting a giveaway it just permanently removes it.
{% endhint %}

### Managing Giveaways

| Command | Description |
| :--- | :--- |
| `-giveaway reroll <message id>` | Chooses a new winner for the specified giveaway |
| `-giveaway list` | Lists all currently active giveaways |

## Giveaway Roles

### Giveaway Blacklist

Members with any of the giveaway blacklisted roles will not be able to join giveaways.  
You can only giveaway blacklist a maximum of 5 roles if you do not have premium enabled in your server.

| Command | Description |
| :--- | :--- |
| `-giveaway blacklist add <@role>` | Adds the specified role to the giveaway blacklist |
| `-giveaway blacklist remove <@role>` | Removes the specified role from the giveaway blacklist |
| `-giveaway blacklist list` | Lists all currently blacklisted roles |

### Giveaway Bypass

Members with any of the bypass roles will be able to join giveaways regardless of if they meet the requirements.  
You can only have a maximum of 5 bypass roles if you do not have premium enabled in your server.

| Command | Description |
| :--- | :--- |
| `-giveaway bypass add <@role>` | Adds the specified role as a bypass role |
| `-giveaway bypass remove <@role>` | Removes the specified role as a bypass role |
| `-giveaway bypass list` | Lists all current bypass roles |

### Giveaway Rolemanager

Members with any of the giveaway manager roles may use **all** giveaway commands.  
You can only have a maximum of 2 giveaway manager roles if you do not have premium enabled in your server.

| Command | Description |
| :--- | :--- |
| `-giveaway rolemanager add <@role>` | Adds the specified role as a giveaway manager role |
| `-giveaway rolemanager remove <@role>` | Removes the specified role as a giveaway manager role |
| `-giveaway rolemanager list` | Lists all current giveaway manager roles |

## 

{% hint style="warning" %}
You can only have a maximum of 5 active giveaways if you do not have premium enabled in your server.
{% endhint %}

