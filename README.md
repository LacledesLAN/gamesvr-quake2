# Quake II Dedicated Server in Docker

Quake II is a first-person shooter video game released in December 1997. It is not a direct sequel to Quake; developer id Software decided to revert to an existing trademark when the game's fast-paced, tactile feel felt closer to a Quake game than a new franchise. The gameplay is very similar to that featured in Quake, in terms of movement and controls, although the player's movement speed has been slowed down, and the player now has the ability to crouch. The multiplayer portion is similar to that of Quake. It can be played as a free-for-all deathmatch game mode, a cooperative version of the single-player game, or as a 1 vs 1 match.

![Quake II Screenshot](https://raw.githubusercontent.com/LacledesLAN/gamesvr-quake2/master/.misc/screenshot.png "Quake II Screenshot")

This repository is maintained by [Laclede's LAN](https://lacledeslan.com). Its contents are intended to be a basic server. For examples of building a customized server from this Docker image browse its related child-project [gamesvr-quake2-freeplay](https://github.com/LacledesLAN/gamesvr-quake2-freeplay). If any documentation is unclear or it has any issues please see [CONTRIBUTING.md](./CONTRIBUTING.md).

This docker image contains the original server software along with [Q2PRO](https://github.com/skullernet/q2pro) for extra functionality and troubleshooting. Also included are compiled versions of [ctf for yquake 2](https://github.com/yquake2/ctf), [OpenFFA](https://github.com/skullernet/openffa), [OpenTDM](https://github.com/skullernet/opentdm),[Lithium](https://github.com/QwazyWabbitWOS/lithium),   and [OpenRocket Arena 2 by packetflinger](https://github.com/packetflinger/openra2).

> Q2PRO is released under GPLv2. It sources can be found at [github.com/skullernet/q2pro](https://github.com/skullernet/q2pro).

## Linux

[![linux/amd64](https://github.com/LacledesLAN/gamesvr-quake2/actions/workflows/build-linux-image.yml/badge.svg?branch=master)](https://github.com/LacledesLAN/gamesvr-quake2/actions/workflows/build-linux-image.yml)

### Download

``` shell
docker pull lacledeslan/gamesvr-quake2;
```

### Run Self Tests

The image includes a test script that can be used to verify its contents. No changes or pull-requests will be accepted to this repository if any tests fail.

``` shell
docker run -it --rm lacledeslan/gamesvr-quake2 ./ll-tests/gamesvr-quake2.sh;
```

### Run Simple Interactive Server using stock server

``` shell
docker run -it --rm --net=host lacledeslan/gamesvr-quake2 ./quake2 +set dedicated 1 +map q2dm1;
```

### Run A Q2Pro Server

``` shell
docker run -it --rm --net=host lacledeslan/gamesvr-quake2 ./q2pro_server_x64 +set dedicated 1 +map q2dm1;
```

### Run A Q2Pro Server - CTF Mod

``` shell
docker run -it --rm --net=host lacledeslan/gamesvr-quake2 ./q2pro_server_x64 +set dedicated 1 +game ctf +map q2ctf1 +exec server.cfg;
```

### Run A Q2Pro Server - Rocket Arena Mod

``` shell
docker run -it --rm --net=host lacledeslan/gamesvr-quake2 ./q2pro_server_x64 +set dedicated 1 +game arena +map ra2map1 +exec arenaconfig.cfg;
```

## Getting Started with Game Servers in Docker

[Docker](https://docs.docker.com/) is an open-source project that bundles applications into lightweight, portable, self-sufficient containers. For a crash course on running Dockerized game servers check out [Using Docker for Game Servers](https://github.com/LacledesLAN/README.1ST/blob/master/GameServers/DockerAndGameServers.md). For tips, tricks, and recommended tools for working with Laclede's LAN Dockerized game server repos see the guide for [Working with our Game Server Repos](https://github.com/LacledesLAN/README.1ST/blob/master/GameServers/WorkingWithOurRepos.md). You can also browse all of our other Dockerized game servers: [Laclede's LAN Game Servers Directory](https://github.com/LacledesLAN/README.1ST/tree/master/GameServers).
