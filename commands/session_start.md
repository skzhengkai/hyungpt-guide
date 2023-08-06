# session start

The `/session start` command starts a conversation session with hyunGPT in the current channel.

## Usage
```
/session start
```

Optionally pass `[create_thread:true]` to have hyunGPT create a thread for the session to be activated in. 

## Functionality

- Initiates a persistent session where hyunGPT will converse.

- Session data like history is stored for continuity.

- Creates thread if `create_thread` passed.

- Requires accepting TOS with a button.

## Examples

Starting session in channel:
```
/session start
```

Starting in new thread:
```
/session start [create_thread:true]
```
