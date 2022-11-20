

SnipeBot is a Discord bot that allows you to "snipe" deleted messages, edited messages, and removed reactions. Deleted messages that had images and other attachments are also tracked.

"Snipes" are only held for a while, so make sure you snipe while you can!

### [Invite](https://discord.com/api/oauth2/authorize?client_id=755582602366287882&permissions=274945403968&scope=bot%20applications.commands)


## FAQ

### What is the prefix?

All user commands use Discord's slash commands system. All commands and some hidden commands can be accessed using the `~` prefix, however slash commands are the recommended way to interact with the bot.

### How do I change the prefix?

You cannot change the prefix of this bot.

### How long are "snipes" stored?

Snipes are stored for a short period after they are removed (currently between 10 and 20 minutes). This is subject to change.


## Support Server

If you need help with the bot, please join our [support server][support server].

### Beta testing features

If you'd like to Beta test new features, please join the [support server][support server] and you'll know about new features before they are officially added to the bot and will be able to test them out and provide feedback.

### Bug Reports

Please report bugs in the [support server][support server].

[support server]: https://discord.gg/f64pfnqbJJ

# Changelog

# Changes (10-24-2022)
## Changes to snipes

- All snipes now take an optional `channel` that you so you can snipe in different channels.
- All options for all commands have help text now.
- All attachments on deleted messages are now tracked again rather than just images.

### Removing snipes
The ability to remove snipes has been added.

**Note:** All commands that remove snipes require ***__Manage Messages__*** permissions unless overridden by you in your server's Integrations settings. Changing this requirement is not recommended.

#### The following commands remove snipes
- rmsnipe: One snipe
- rmsnipes: All snipes
- rmesnipe: One edit snipe
- rmesnipes: All edit snipes
- rmrsnipe: One reaction snipe
- rmresnipes: All reaction snipes

## Other
- Fixed an issue where you can't snipe someone who has left or been kicked/banned from your server.
- `aim` now takes a User instead of a Member. This means you can now input any user's id and it will generate an aim for them.
- Various performance improvements

# Changes 10-26-2022

- Fixed `rmesnipe` not working properly.

# Changes 11-8-2022

### Added paginated snipe commands.
- isnipe
- iesnipe
- irsnipe

The name/method of using these is subject to change in the near future if I think of a better way.

These commands give you an interactive way to look through all of the snipes in a channel without running commands repeatedly.

### Increased message cache size.

The message cache size has increase by 2.5x. This means that more deleted/edited messages will be caught.

# Changes 11-19-22

Changed embed color scheme.
