# Join plugin

The join plugin provides configurable options to give your users a role when they join!

When `security` is enabled in configuration, Speedboat will wait X minutes before the user gains their role. To view the defaults and learn how to configurate them, continue reading.

## Configuration Options
| Option  | Description                                                               | Type | Default |
|---------|---------------------------------------------------------------------------|------|---------|
| join_role | Role ID that is set for users when they meet the critera.               | id | none    |
| security  | Whether the servers security settings influence how long it takes a user to gain their join_role.   | bool | true    |
| advanced  | A mapping of verification levels to Advanced Configurations | dict | empty   |

## Advanced Configurations
| Option  | Description                                                               | Type | Default |
|---------|---------------------------------------------------------------------------|------|---------|
| low     | Time in minutes until a user gains their join_role for servers with low verification. | int | 0 |
| medium  | Time in minutes until a user gains their join_role for servers with medium verification. | int | 5 |
| high    | Time in minutes until a user gains their join_role for servers with high verification.  | int | 10 |
| highest | Time in minutes until a user gains their join_role for servers with extreme/highest verification. | int | 30 |


## Configuration Example

```yaml
join:
  join_role: 814574906044973087
  security: false
  advanced:
    low: 0
    medium: 5
    high: 10
    highest: 30
```
