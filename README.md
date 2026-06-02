# BWStatsToDC

A Discord-integrated BedWars statistics plugin for Spigot servers.

BWStatsToDC allows players to view BedWars statistics and leaderboards directly from Discord using slash commands, complete with automatically generated stat cards and leaderboard images.

## Features

* Discord slash command support
* Player statistics lookup
* Wins leaderboard
* Kills leaderboard
* Beds destroyed leaderboard
* Automatic image generation
* SQLite database support
* Configurable Discord channel
* Configurable database path
* Configurable server branding
* Lightweight setup

## Commands

### Player Statistics


/bwstats <player> 

Displays a player's BedWars statistics.


### Leaderboards

/bwlb wins 

/bwlb kills 

/bwlb beds 

Displays the top players for the selected statistic.

## Configuration

Example configuration:
yaml
bot-token: "YOUR_DISCORD_BOT_TOKEN"
allowed-channel: 123456789012345678
database:
  path: "plugins/BedWars1058/Cache/shop.db"
branding:
  server-name: "My Server"


## Requirements

* Java 21
* Discord Bot Token
* Spigot Server
* SQLite BedWars Database

## Installation

1. Download the latest release.
2. Place BWStatsToDC.jar into your plugins folder.
3. Start the server once.
4. Configure config.yml.
5. Add your Discord bot token.
6. Set your Discord channel ID.
7. Restart the server.

## Permissions

No Minecraft permissions are required.

Discord users can access commands in the configured Discord channel.

## Screenshots

Stat cards and leaderboard images are generated automatically and sent directly in Discord.

## Support

For bug reports, feature requests, or support, please use the GitHub Issues page.

## License

All Rights Reserved.

You may use this plugin on your server.

You may not:

* Redistribute the plugin
* Reupload the plugin
* Sell copies of the plugin
* Claim ownership of the plugin
* Decomplie, Modify and redistribute the plugin without permission

## Version

Current Release: v1.0
