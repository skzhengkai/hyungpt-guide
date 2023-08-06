# session settings

The `/session settings` command shows or changes settings for the active session.

## Usage

View current settings:
```
/session settings
```

Change a setting:
```
/session settings [name] [value]
```

## Settings

- `persona_name` - Who hyunGPT pretends to be.
- `persona_info` - Details about hyunGPT's persona.
- `webhook_url` - Define a Discord webhook URL for hyunGPT to send messages through.
- `vc_voice` - What voice hyunGPT should use if it's in a Discord Voice Chat.
- `nsfw` - Toggle NSFW chats on or off.
- `roleplay` - Toggle Roleplay chats on or off.
- `reply_mode` - Set if messages should be in the form of replies or not.
- `respond_to_pings_only` - Set if hyunGPT should only read messages if it begins with @hyunGPT.

## Examples

View settings:
```
/session settings
```

Change setting:
```
/session settings [persona_name:"Jane Doe"]
```
