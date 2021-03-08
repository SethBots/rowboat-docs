# Utility Plugin

The utility plugin provides a number of useful and fun commands

## Commands

| Name | Description | Default Level | Usage |
|------|-------------|---------------|-------|
| `!cat` | Returns a random image of a cat | Default | `!cat` |
| `!emoji {emoji}` | Returns information on the given emoji | Default | `!emoji :smiley:` |
| `!info {user}` | Returns information on the given user | Default | `!info 351776065477279745` OR `!info @Speedboat#9599`|
| `!jumbo {emojis}` | Returns 128x128px images of the given emoji | Default | `!jumbo :cat: :dog: :rabbit:` |
| `!random coin` | Flips a coin and returns the result | Default | `!random coin` |
| `!random number [end number] [start number]` | Returns a random number from 0-10 or in a range if specified | Default | `!random number` OR `!random number 50 20` |
| `!r add {duration} {content}` OR `!remind {duration} {content}` | Adds a reminder. Bot will mention the user after the specified duration with the given message | Default | `!r add 24h update announcements` OR `!remind 24h update announcements` |
| `!r clear` | Clears all of the user's reminders | Default | `!r clear` |
| `!search {query}` | Searches for usernames that match given query | Default | `!search b1nzy` |
| `!seen {user}` | Returns the timestamp of when the bot last saw a message from given user | Default | `!seen 351776065477279745` OR `!seen @Speedboat#9599` |
| `!server [guild]` | Returns information on the current server or the Server ID if given | Default | `!server` OR `!server 290923757399310337` |

## Configuration Example

```yml
utilities: {}
```

That's it. Simply enable the plugin. There is no further configuration for this plugin.
