# Lavalink
Standalone audio sending node based on Lavaplayer and JDA-Audio.
Allows for sending audio without it ever reaching any of your shards.

Being used in production by FredBoat, Dyno, Rythm, LewdBot, and more.

[![JDA guild](https://discordapp.com/api/guilds/125227483518861312/embed.png?style=banner2)](https://discord.gg/jtAWrzU)

## Features
* Powered by Lavaplayer
* Minimal CPU/memory footprint
* Twitch/YouTube stream support
* Event system
* Seeking
* Volume control
* REST API for resolving lavaplayer tracks (used for non-JVM clients)
* Statistics (good for load balancing)
* Basic authentication
* Prometheus metrics
* Docker images

## Changelog

Please see [here](CHANGELOG.md)

## Client libraries:
### Supports 3.x and older:
* [Lavalink-Client](https://github.com/FredBoat/Lavalink-Client) (JDA or generic, Java)
* [LavaClient](https://github.com/SamOphis/LavaClient) (Java)
* [Lavalink.py](https://github.com/Devoxin/Lavalink.py) (discord.py, Python)
* [pylava](https://github.com/Pandentia/pylava) (discord.py, Python)
* [SandySounds](https://github.com/MrJohnCoder/SandySounds) (JavaScript)
* [eris-lavalink](https://github.com/briantanner/eris-lavalink) ([eris](https://github.com/abalabahaha/eris), JavaScript)
* [discord.js-lavalink](https://github.com/MrJacz/discord.js-lavalink/) ([discord.js](https://github.com/discordjs/discord.js), JavaScript)
* [Lavalink.NET](https://github.com/Dev-Yukine/Lavalink.NET) (.NET)
* [DSharpPlus.Lavalink](https://github.com/DSharpPlus/DSharpPlus/tree/master/DSharpPlus.Lavalink) ([DSharpPlus](https://github.com/DSharpPlus/DSharpPlus/), .NET)
* Or [create your own](https://github.com/Frederikam/Lavalink/blob/master/IMPLEMENTATION.md)

### Supports 2.x:
* [Magma](https://github.com/initzx/magma/) (discord.py, Python)
* [eris-lavalink](https://github.com/briantanner/eris-lavalink) (Eris, JavaScript)
* [discord.js-lavalink](https://github.com/MrJacz/discord.js-lavalink/) (Discord.js, JavaScript)
* Or [create your own](https://github.com/Frederikam/Lavalink/blob/master/IMPLEMENTATION.md)

## Server configuration
Download from [the CI server](https://ci.fredboat.com/viewLog.html?buildId=lastSuccessful&buildTypeId=Lavalink_Build&tab=artifacts&guest=1)

Put an `application.yml` file in your working directory. [Example](https://github.com/Frederikam/Lavalink/blob/master/LavalinkServer/application.yml.example)

Run with `java -jar Lavalink.jar`

Docker images are available on the [Docker hub](https://hub.docker.com/r/fredboat/lavalink/).

[![Docker Pulls](https://img.shields.io/docker/pulls/fredboat/lavalink.svg)](https://hub.docker.com/r/fredboat/lavalink/) [![Docker layers](https://images.microbadger.com/badges/image/fredboat/lavalink:dev.svg)](https://microbadger.com/images/fredboat/lavalink:dev "Get your own image badge on microbadger.com")

# Acknowledgements
This project contains modified code from https://github.com/sedmelluq/jda-nas v1.0.5
