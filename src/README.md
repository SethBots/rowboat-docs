# Speedboat

Speedboat is a modernized fork of rowboat, a moderation and utilitarian bot built for large Discord servers. It's a bot that was built to be highly configurable, and allow server admins to modify functionality based on the requirements of individual servers. The freely hosted version of Speedboat is private and [you must reach out to be approved.](https://discord.gg/qT7qGq6) Approval can be given especially to high-traffic servers. Speedboat is [open-source](https://github.com/SethBots/speedboat).

## Use Cases

### r/Overwatch

With over 50,000 members, r/Overwatch is one of Discord's largest and most complicated servers. Previously the administration team had put together a multitude of custom-written bots with various functionality, but when moving to Speedboat they where able to eliminate these entirely. Speedboat provides r/Overwatch with the level of protection and auditing required to run such a high activity server.

#### Multiple Mod Logs

By using Speedboat's support for multiple mod logs, r/Overwatch's admins are able to split and categorize logs into various channels, reducing noise without sacrificing logging.

#### Spam Prevention

By turning on Speedboat's spam prevention, r/Overwatch takes a huge burden off moderators and ensures the server is safe even when nobody is watching. With the high level of configurability they were able to ensure a level of security which does not impact normal chat, but catches bad actors quickly and efficiently.

## User Testimonials

### Looney - Events and Community for Discord

> Speedboat has allowed us to efficiently scale the moderation teams of our large public and private community servers, without placing extra burden on our volunteer moderators or sacrificing auditability.

### PapaSmurf - Community Moderator, Server Owner and Discord Partner

> Speedboat has helped me manage the multiple servers I run with quick and easy access to logging information.

### Tachyon - Community Moderator and Discord Hypesquad Member

> Speedboat allows for easy logging and server administration and moderation; it plays an important role in any discord community and is one of the most responsive bots out there.

### Wolfiri - Community Moderator, Server Owner and Discord Partner

> Before Speedboat came along, I was stuck using poorly built and inadequate bots with confusing in-client configurations or limited dashboard options. Now with Speedboat, I'm able to easily customize every option and plugin, giving me only the features I want and exactly how I want them. The level of customization is unmatched by any other bot. My moderation team now has the tools at their disposal to handle anything thrown at them without needing extensive training to use these tools. I also no longer have to worry about missing anything with the comprehensive moderation log feature. Every change is tracked from nicknames to deleted messages. Not only does Speedboat have the best moderation tools, the utility commands are also heavily used on my servers. We have reminders, multi-jumbo emoji, and random cats! Every feature on Speedboat is well thought out and built with the user's experience in mind. Speedboat is an exceptional bot and has truly enhanced my experience on Discord -- I can't imagine moderating a server without it!

## Plugins

- Administration
  - Banning, kicking, muting
  - Managing and tracking infractions and reasons per user and moderator
  - User persistence (resetting roles/nickname/etc when users leave and rejoin)
  - Chat cleaning and archiving
  - Granular role management (adding/removing roles)
  - Invite pruning
  - Reactions pruning
  - Voice logs
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


