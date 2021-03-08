# Moderator Command Quick-Reference

## Punishments

| Name | Description | Default Level | Usage |
|------|-------------|---------------|-------|
| `!warn {user} [reason]` | Adds a warning infraction to a user | Moderator | `!warn 351776065477279745 1st warning, spamming emoji` OR `!warn @Speedboat#9599 2nd warning, going off-topic` |
| `!mute {user} [reason]` | Mutes a user. This will only work if `mute_role` is set in the config | Moderator | `!mute 351776065477279745 spamming` OR  `!tempmute @Speedboat#9599 60m spamming` |
| `!unmute {user}` | Unmutes a user | Moderator | `!unmute 351776065477279745` |
| `!tempmute {user} {duration} [reason]` | Temporarily mutes a user. Will only work if `mute_role` is set in the config | Moderator | `!tempmute 351776065477279745 30m spamming` OR `!tempmute @Speedboat#9599 30m spamming` |
| `!kick {user} [reason]` | Kicks the user from the server | Moderator | `!kick 351776065477279745 spamming` OR `!kick @Speedboat#9599 spamming` |
| `!ban {user} [reason]` | Bans a user from the server | Moderator | `!ban 351776065477279745 spamming` OR `!ban @Speedboat#9599 spamming` |
| `!unban {user} [reason]` | Unbans a user | Moderator | `!unban 351776065477279745` |
| `!forceban {User ID} [reason]` | Force bans a user who is not currently in the server | Moderator | `!forceban 351776065477279745 spamming` |
| `!softban {user} [reason]` | Softbans (bans/unbans) a user and deletes the user's messages sent within the last 7 days | Moderator | `!softban 351776065477279745 spamming` OR `!softban @Speedboat#9599 spamming` |
| `!tempban {user} {duration} [reason]` | Temporarily bans a user | Moderator | `!tempban 351776065477279745 5h spamming` OR `!tempban @Speedboat#9599 5h spamming` |


## Admin Utilities

| Name | Description | Default Level | Usage |
|------|-------------|---------------|-------|
| `!clean all [count]` | Cleans (deletes) [count] many messages in the current channel | Moderator | `!clean all 20` |
| `!clean user {user} [count]` | Cleans [count] many messages a given user sent in the current channel | Moderator | `!clean user 351776065477279745 50` |
| `!clean bots [count]` | Cleans [count] many messages sent by bots in the current channel | Moderator | `!clean bots 30` |
| `!clean cancel` | Cancels any cleaning process running in current channel | Moderator | `!clean cancel` |
| `!reactions clean {user} [count] [emoji]` | Removes the most recent count of reactions from a given user | Moderator | `!reactions clean 351776065477279745` OR `!reactions clean @Speedboat#9599 30` OR `!reactions clean 351776065477279745 20 :thinking:` |
| `!archive (here / all) [count]` | Archives [count] many messages in the current channel | Moderator | `!archive all 50` OR `!archive here 50` |
| `!archive user {user} [count]` | Archives [count] many messages that a given user sent in the current guild | Moderator | `!archive user 351776065477279745 100` OR `!archive user @Speedboat#9599 100` |
| `!archive channel {channel} [count]` | Archives [count] many messages in the given channel | Moderator | `!archive channel 289482554250100736 20` |
| `!search {query}` | Searches for usernames that match given query | Default | `!search b1nzy` |
| `!role add {user} {role} [reason]` | Adds a role to a user | Moderator | `!role add 351776065477279745 Moderator Promotion from Member` OR `!role add Speedboat#9599 Admin Pretty good Moderator` |
| `!role remove {user} {role} [reason]` | Removes a role from a user | Moderator | `!role remove 351776065477279745 Administrator Demoted for being bad at job` OR `!role remove Speedboat#9599 Mod Terrible moderator` |
| `!r add {duration} {content}` OR `!remind {duration} {content}` | Adds a reminder. Bot will mention the user after the specified duration with the given message | Default | `!r add 24h update announcements` OR `!remind 24h update announcements` |
| `!r clear` | Clears all of the user's reminders | Default | `!r clear` |
| `!voice log {user}` | Displays a list of a given user's recent voice channel activity | Moderator | `!voice log 351776065477279745` OR `!voice log @Speedboat#9599` |


## Infractions

| Name | Description | Default Level | Usage |
|------|-------------|---------------|-------|
| `!inf search {query}` | Searches infractions database for given query | Moderator | `!inf search 351776065477279745` OR `!inf search Speedboat#9599` OR `!inf search spamming`
| `!inf info {inf#}` | Presents information on the given infraction | Moderator | `!inf info 1274`
| `!inf duration {inf#} {duration}` | Updates the duration of the given infraction. Duration starts from time of initial action | Moderator | `!inf duration 1274 5h` |
| `!inf reason {inf#} {reason}` | Updates the reason of a given infraction | Moderator | `!inf reason 1274 rude behaviour towards staff` |


## Starboard

| Name | Description | Default Level | Usage |
|------|-------------|---------------|-------|
| `!stars block {user}` | Prevents the user from starring any messages and prevents their messages from being starred | Moderator | `!stars block @Speedboat#9599` OR `!stars block 351776065477279745` |
| `!stars unblock {user}` | Unblocks a user from the starboard | Moderator | `!stars unblock @Speedboat#9599` OR `!stars unblock 351776065477279745` |
| `!stars hide {mid}` | Hides a starred message from the starboard | Moderator | `!stars hide 320312743842545664` |
| `!stars unhide {mid}` | Unhides a hidden message | Moderator | `!stars unhide 320312743842545664` |
| `!stars lock` | Prevents any new starred messages from being posted to the starboard | Administrator | `!stars lock` |
| `!stars unlock` | Enables starred messages to be posted | Administrator | `!stars unlock` |
