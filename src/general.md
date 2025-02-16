## General Configuration

### Web

```yml
web:
  194861788926443520: admin  # DeJay
  194861788926443520: editor # Also DeJay
  351776065477279745: viewer # Speedboat
```

Web determines which users are able to view the configuration dashboard for the server. Commenting a line with the Username above each ID helps with organization.

User ID is used to assign ranks. There are three ranks you can assign: admin, editor,  viewer. Admin can add more users (including other Admins), edit, and view the dashboard. Editor can edit and view the dashboard. Viewer can only view.

### Nickname

```yml
nickname: SP33DBOAT
```

Set a nickname for the bot! Nickname is applied upon reload of the bot.

### Levels

```yml
levels:
  290295853124550657: 100 #Admin
  295476842935353345: 50 #Moderator
  298993418577903616: 10 #Trusted
```

This is where you assign levels to each role! Remember, the default level is 0 if a user doesn't have one of the listed roles. Users will have the highest level of the roles they're assigned.

By default, each level has a certain rank associated with it: 0 - Default, 10 - Trusted, 50 - Mod, 100 - Admin. You can view the default rank required for each command by looking at the Commands section for the plugin.

Levels can be assigned anywhere from 0 to 100, keeping in mind the default permissions given in the Speedboat Docs.

### Commands and Overrides

```yml
commands:
  prefix: '!'
  overrides:
  - {plugin.name: 'utilities', out: {level: 10}}
  - {group: 'clean', out: {level: 40}}
  - {name: 'mute', out: {level: 40}}
```

Here, you can change your prefix, which is the symbol which begins each command. For example: !ban, !ban, $ban, ^ban, rban

You can also define a list of valid prefixes:

```yml
commands:
  prefixes: ['!', '?']
```

Overrides allow you to customize which levels and roles can use each command, or group of commands.

* `"plugin.name"` is used for all commands in a plugin (hint: every section that's indented one in beneath the "plugins:" section is a plugin)  
* `"group"` is used for commands which have multiple components. Some examples: clean, archive, role, stars)  
* `"name"` is used for all other commands.  
* `"out: {level: }}"` is used to assign the minimum level required to use the command.
* `"out: {disabled: true}}"` is used to disable commands

Taking the configuration above as an example, if you didn't want regular members to use utility commands (such as jumbo, info, and cat), you can set the level of the "utilities" plugin to 10. This means the role must have at least level 10 assigned to use utility commands.
