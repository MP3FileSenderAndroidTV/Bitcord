# Bitcord
A Discord client for old Android <4.x devices. Uses proxy servers for the [HTTP](https://github.com/gtrxAC/discord-j2me/blob/main/proxy) and [gateway](https://github.com/gtrxAC/discord-j2me-server) connection. Currently work-in-progress.

## How to build

# PC Method
1. Install Android Studio. Android Studio 1.0 should work though newer versions should work fine.
2. Fork the repository on GitHub.
3. Compile the APK.
4. Install on Device.

# Non PC method (Cloud IDE):
1. Fork the repository on GitHub.
2. Import the repo on Gitpod or Replit.
3. Compile the APK.
4. Install the Device.

## Status
### Working
* Logging in
* Server list
* Channel list
* Direct messages and group DMs
* Message reading
* Message sending
* Gateway/live message updates
* Attachment viewing

### Not implemented
* Message editing
* Message deleting
* Replying to messages
* Reading older messages
* Attachment sending
* Unread message indicators
* Jumping to messages (e.g. replies)
* Ping indicators
* Reactions and emojis
* Settings

## Credits
- [@gtrxac](https://github.com/gtrxAC) for his [Discord J2ME](https://github.com/gtrxAC/discord-j2me) project where most of the code came from.
- [@shinovon](https://github.com/shinovon) for their [JSON library](https://github.com/shinovon/NNJSON) (yes I know I can just use any other JSON library that works with Java 7 or whatever the hell Android 1.x uses but I'm too lazy so screw it)
