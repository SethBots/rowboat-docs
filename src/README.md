# Speedboat

Speedboat is a modernized fork of rowboat, a moderation and utilitarian bot built for large Discord servers. It's a bot that was built to be highly configurable, and allow server admins to modify functionality based on the requirements of individual servers. The freely hosted version of Speedboat is private and [you must reach out to be approved.](https://discord.gg/qT7qGq6) Approval can be given especially to high-traffic servers. Speedboat is [open-source](https://github.com/SethBots/speedboat).

## Use Cases

### bbnomula

With over 30,000 members, the bbno$ Discord is one of hip-hops and most complicated servers. Previously the administration team ran on a pletora of public bots with various functionality, but when moved to Speedboat they where able to eliminate these entirely. Speedboat provides bbno$ with the level of protection and auditing required.

#### Multiple Mod Logs

By using Speedboat's support for multiple mod logs, r/Overwatch's admins are able to split and categorize logs into various channels, reducing noise without sacrificing logging.

#### Spam Prevention

By turning on Speedboat's spam prevention servers take a huge burden off moderators and ensures the server is safe especially when nobody is watching. With the high level of configurability they were able to ensure a level of security which does not impact normal chat, but catches bad actors quickly and efficiently.

## User Testimonials

### Removed

## Plugins

- Administration
  - Banning, kicking, muting
  - Managing and tracking infractions and reasons per user and moderator
  - User persistence (resetting roles/nickname/etc when users leave and rejoin)
  - Chat cleaning and archiving
  - Granular role management (adding/removing roles)
  - Invite pruning
  - Reactions pruning
- Censor
  - Zalgo prevention
  - Whitelisting of invites based on vanity url or destination server
  - Whitelisting of urls and domains
  - Blocking of words and tokens
  - Level based configuration granularity
- Mod Log
  - Granular logging of events
  - Support for multiple channels
  - Ability to include exact timestamps in specific timezone
  - Ignoring and filtering of specific users (helpful for music/etc bots)
  - Highlighting newly created accounts on join
  - Support for automatic batching during high-throughput periods (user purges, raids, cleans, etc) prevents log messages from backing up
- Reddit
  - Support for multiple subreddit sources and channel destinations
  - Support for filtering nsfw content
- Spam
  - Highly configurable spam thresholds which can help block:
    - Message Spam
    - Mention Spam
    - Link Spam
    - Emoji Spam
    - Newline/Large Message Spam
    - Attachment/Upload Spam
    - Duplicated Message Spam / Raids
  - Per-rule and global punishment configuration can ban, tempban, mute, tempmute, or kick users
  - Auto-cleaning of messages based on rules
  - Optional raid prevention
- Starboard
  - Highly configurable
  - In-depth stats and leaderboard
  - Ability to entirely block users from starboard
  - Ability to lock/unlock starboard on-demand
- Utilities
  - Long-term persistent reminders
  - Random number and coin generation
  - User information, including last seen time
  - Server information
  - User search
  - CAT PHOTOS
