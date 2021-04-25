# Contributing

First off, thank you for considering contributing to `gamesvr-quake2`. It's people like you that make Laclede's LAN such a great community.

## Did you find a bug or have questions?

Let us know by using [GitHub issues](https://github.com/LacledesLAN/gamesvr-quake2/issues) on this repository.

## Have a fix or feature?

[Fork this repository](https://help.github.com/articles/fork-a-repo), create a branch with a descriptive name, and submit a pull request. A project maintainer will remove and either merge or provide feedback.

## A few notes about Quake2

This docker container does contain [Q2pro](https://github.com/skullernet/q2pro) and the stock game server software running within Ubuntu, which means for all mods will require the proper binary files such as gamei386.so and gamex86_64.so. It is best to compile from sourceode in a 64 bit version of ubuntu order to get the right version.
 
Since this is to be an example server, to help with configuration It is best to put example config and maplist files in as placeholders to help with documentation and configuration. We are always looking to add and preserve game mods and addons, we just still want to make this a basic server to build on. Just consider the /dist/app to be the same as the quake2 base directory where the server binary is.
