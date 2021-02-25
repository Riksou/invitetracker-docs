# Variables

You can use several variables while configuring **join messages**, **leave messages** and **join DM messages**.

**Variables for your messages**

| Variable | Description | Where to use |
| :--- | :--- | :--- |
| %member% | Member's name and discriminator | `JOIN`, `LEAVE`, `JOIN DM` |
| %member\_name% | Member's name | `JOIN`, `LEAVE`, `JOIN DM` |
| %member\_discriminator% | Member's discriminator | `JOIN`, `LEAVE`, `JOIN DM` |
| %member\_mention% | Mention the member | `JOIN`, `LEAVE`, `JOIN DM` |
| %member\_id% | Member's Discord ID | `JOIN`, `LEAVE`, `JOIN DM` |
| %member\_created% | When the member made their account | `JOIN`, `LEAVE`, `JOIN DM` |
| %member\_created\_ago% | How many days ago the member made their account | `JOIN`, `LEAVE`, `JOIN DM` |
| %member\_joined% | When the member joined the server | `LEAVE` |
| %member\_joined\_ago% | How many days ago the member joined the server | `LEAVE` |
| %member\_join\_count% | How many times the member joined the server | `JOIN`, `LEAVE`, `JOIN DM` |
| %member\_leave\_count% | How many times the member left the server | `JOIN`, `LEAVE`, `JOIN DM` |
| %inviter% | Inviter's name and discriminator | `JOIN`, `LEAVE`, `JOIN DM` |
| %inviter\_name% | Inviter's name | `JOIN`, `LEAVE`, `JOIN DM` |
| %inviter\_discriminator% | Inviter's discriminator | `JOIN`, `LEAVE`, `JOIN DM` |
| %inviter\_mention% | Inviter's mention | `JOIN`, `LEAVE`, `JOIN DM` |
| %inviter\_id% | Inviter's Discord ID | `JOIN`, `LEAVE`, `JOIN DM` |
| %inviter\_invites% | Inviter's number of total invites | `JOIN`, `LEAVE`, `JOIN DM` |
| %inviter\_reg\_invites% | Inviter's number of regular invites | `JOIN`, `LEAVE`, `JOIN DM` |
| %inviter\_leave\_invites% | Inviter's number of leave invites | `JOIN`, `LEAVE`, `JOIN DM` |
| %inviter\_fake\_invites% | Inviter's number of fakes invites | `JOIN`, `LEAVE`, `JOIN DM` |
| %inviter\_bonus\_invites% | Inviter's number of bonus invites | `JOIN`, `LEAVE`, `JOIN DM` |
| %guild\_name% | Server's name | `JOIN`, `LEAVE`, `JOIN DM` |
| %guild\_count% | Number of members in the server | `JOIN`, `LEAVE`, `JOIN DM` |
| %invite\_code% | The invite code the user used | `JOIN` |
| %invite\_uses% | The number of uses the invite code has | `JOIN` |
| %invite\_url% | The invite url | `JOIN` |



