# Setting Up Speedboat

## Adding the Bot

Message DeJay#1337, or join https://inv.wtf/dejay and post your request with the server ID and optionally an invite to the server in the #discussions channel. Minimum requirements may vary server by server, but any size Minecraft Community may get the bot on request. When accepted, you will be messaged with further instructions will be given. If declined, you may reapply if there is significant change to your server (more members, different topic, partnership, etc.)

## How to Set Up

Once Speedboat has been added to your server, go to https://speedboat.dejay.dev/ to edit your server's configuration. Use the sidebar to read about each plugin, then use the example below along with the information in the sidebar to set up your own customized Speedboat installation.

Below is a blank configuration example with many important plugins already setup. While you can simply copy-paste this to your own server's configuration and fill in the blanks to have a perfectly usable Speedboat, it's highly encouraged that you read through the full documentation to understand each component and customize Speedboat to your server's needs.

```yml
web:
  000000000000000000: admin  # Username
  000000000000000000: editor # Username
  000000000000000000: viewer # Username

commands:
  prefix: '!'
  overrides: []

levels:
  000000000000000000: 000 # Role

nickname: R0WB0AT

plugins:

  utilities: {}

  admin: {}

  infractions:
    mute_role: 000000000000000000

  modlog:
    channels:
      00000000000000000000000:
        exclude: []
        include: []
    ignored_users: []

  spam:
    levels:
      0:
        punishment: TEMPMUTE
        punishment_duration: 120
        max_messages:
          count: 10
          interval: 7
        max_mentions:
          count: 8
          interval: 30
        max_links:
          count: 10
          interval: 60
        max_emojis:
          count: 100
          interval: 120
        max_newlines:
          count: 60
          interval: 120
        max_duplicates:
          count: 5
          interval: 30

  censor:
    levels:
      0:
        filter_invites: true
        filter_domains: false
        invites_whitelist: ['discord-developers', 'discord-testers', 'discord-api', 'discord-linux']
        blocked_words: ['word1', 'word2', 'word3']
```
