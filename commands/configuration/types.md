---
description: View all the different invite and message types.
---

# Types

## Invite Types

Invite Tracker allows each user to have a specific amount of **regular**, **left**, **bonus** and **fake** invites. Each invite type has a different meaning.

| Invite Type | Description |
| :--- | :--- |
| `Regular` | This invite is added to the inviter when someone joins with their invite, no matter what. |
| `Left` | This invite is added to the inviter of the person who joined with their invite when they leave the server. |
| `Bonus` | This type of invite can be added via commands by administrators or people with the management role. |
| `Fake` | This type of invite is added to the inviter when someone joins with their invite, but the new member's account is less than 3 days old. |

## Message Types

### Main Message Types

| Type | Description |
| :--- | :--- |
| `Join` | This message is sent in the server whenever a user joins it. |
| `JoinDM` | This message is sent as a direct message to a user who just joined the server. |
| `Leave` | This message is sent in the server whenever a user leaves it. |

### Sub-Message Types

| Type | Description |
| :--- | :--- |
| `Normal` | The message sent when the user joined the server via "normal" means. |
| `Vanity` | The message sent when the user joined the server via a vanity link. |
| `Bot` | The message sent when a bot joined/left the server. |
| `No-Perm` | The message sent when Invite Tracker does not have enough permissions to see how a user joined. |
| `Unknown` | The message sent when Invite Tracker does not know how a user joined the server. |

{% hint style="info" %}
The `unknown` message is very rare. There are only a few reasons why you would get this message:

**1:** Invite Tracker can not see the channel to which the invite was directed.  
\(Permission problem which can be fixed easily by giving admin to Invite Tracker\)

**2:** Multiple people joined at the same time.   
\(Impossible to fix\)

**3:** The server's invites were recently reset.  
\(Only way to avoid this is by not resetting, to begin with\)
{% endhint %}

