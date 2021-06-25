---
description: >-
  The explanation for all the configuration commands available for Invite
  Tracker.
---

# Configuration

## Channel Configuration

### Configchannel

| Command | Description |
| :--- | :--- |
| `-configchannel join <#channel>` | Sets the channel where **join** messages will be sent |
| `-configchannel leave <#channel>` | Sets the channel where **leave** messages will be sent |

## Message Configuration

### Configenable

#### Configenable Join

| Command | Description |
| :--- | :--- |
| `-configenable join true` | Enables **join** messages |
| `-configenable join false` | Disables **join** messages |

#### Configenable JoinDM

| Command | Description |
| :--- | :--- |
| `-configenable joindm true` | Enables **joindm** messages |
| `-configenable joindm false` | Disables **joindm** messages |

#### Configenable Leave

| Command | Description |
| :--- | :--- |
| `-configenable leave true` | Enables **leave** messages |
| `-configenable leave false` | Disables **leave** messages |

### Configmessage

#### Configmessage Join

| Command | Description |
| :--- | :--- |
| `-configmessage join normal <message>` | Configures the **normal join** message |
| `-configmessage join vanity <message>` | Configures the **vanity join** message |
| `-configmessage join bot <message>` | Configures the **bot join** message |
| `-configmessage join no-perm <message>` | Configures the **no-perm** **join** message |
| `-configmessage join unknown <message>` | Configures the **unknown** **join** message |

#### Configmessage JoinDM

| Command | Description |
| :--- | :--- |
| `-configmessage joindm normal <message>` | Configures the **normal** **joinDM** message |
| `-configmessage joindm vanity <message>` | Configures the **vanity** **joinDM** message |
| `-configmessage joindm bot <message>` | Configures the **bot** **joinDM** message |
| `-configmessage joindm no-perm <message>` | Configures the **no-perm** **joinDM** message |
| `-configmessage joindm unknown <message>` | Configures the **unknown joinDM** message |

{% hint style="warning" %}
When defining a **Join DM** message, make sure to specify `normal` for the message type.
{% endhint %}

#### Configmessage Leave

| Command | Description |
| :--- | :--- |
| `-configmessage leave normal <message>` | Configures the **normal leave** message |
| `-configmessage leave vanity <message>` | Configures the **vanity leave** message |
| `-configmessage leave bot <message>` | Configures the **bot leave** message |
| `-configmessage leave no-perm <message>` | Configures the **no-perm** **leave** message |
| `-configmessage leave unknown <message>` | Configures the **unknown** **leave** message |

### Testmessage

#### Testmessage Join

| Command | Description |
| :--- | :--- |
| `-testmessage join normal` | Tests the **normal** **join** message |
| `-testmessage join vanity` | Tests the **vanity** **join** message |
| `-testmessage join bot` | Tests the **bot join** message |
| `-testmessage join no-perm` | Tests the **no-perm** **join** message |
| `-testmessage join unknown` | Tests the **unknown** **join** message |

#### Testmessage JoinDM

| Command | Description |
| :--- | :--- |
| `-testmessage joindm normal <message>` | Tests the **normal** **joinDM** message |
| `-testmessage joindm vanity <message>` | Tests the **vanity** **joinDM** message |
| `-testmessage joindm bot <message>` | Tests the **bot** **joinDM** message |
| `-testmessage joindm no-perm <message>` | Tests the **no-perm** **joinDM** message |
| `-testmessage joindm unknown <message>` | Tests the **unknown joinDM** message |

#### Testmessage Leave

| Command | Description |
| :--- | :--- |
| `-testmessage leave normal <message>` | Tests the **normal leave** message |
| `-testmessage leave vanity <message>` | Tests the **vanity leave** message |
| `-testmessage leave bot <message>` | Tests the **bot leave** message |
| `-testmessage leave no-perm <message>` | Tests the **no-perm** **leave** message |
| `-testmessage leave unknown <message>` | Tests the **unknown** **leave** message |

{% hint style="info" %}
All different message and invite types are explained [here](types.md)

All different variables and their explanations are located [here](variables.md)
{% endhint %}

## Server Configuration

| Command | Description |
| :--- | :--- |
| `-config` | Shows the configuration settings for the server |

### Sethighestmode

Determines if Invite Tracker assigns all or only the highest reward role.

| Command | Description |
| :--- | :--- |
| `-sethighestmode true` | Sets highest role mode to true |
| `-sethighestmode false` | Sets highest role mode to false |

