---
title: An Corp
excerpt: A Resurrection
date: 2022-11-18 12:15:49
tags:
    - Steam
    - WorldCreator
    - Server
    - Lua
    - Core
    - Network
    - GitHub
photos:
    - logo_boulder_light_1024.png
---


Nearly two years ago CODEX was started as a simple idea, perhaps too simple. Over the past 6 months we've been hard at work expanding that idea and the time has finally come for us to share it with you; CODEX has expanded beyond a standalone MMO and will become a powerful tool/platform for hosting and playing your own online games.

# Public Servers

The server binary files will be available free of charge for anyone to host a Public Server on CODEX. The timeline on when we start distributing the public build is still under consideration but will be sooner rather than later. 

## Core

With the new direction of public servers we felt it important to revisit our LUA script set (the scripts that control the gameplay) to be made suitable for public distribution. Meet **Core**. This is a re-usable set of Lua scripts, akin to a library, to get any new ruleset going. Core will allow us as a community to improve upon the shared set of core scripts that follow some agreed upon rules.

## GitHub

CODEX Public Servers Admins will find all the information they need at GitHub. This will also be our home for ruleset specific scripts (Items/NPCs/Skills/Stats/Etc) which can be placed in a Public Server's Mod folder for use. Even this website's source can be found and edited there, [take a look](https://github.com/corp-por?tab=repositories).

## World Creator

The CODEX client now includes our **World Creator**. Edit terrain, place trees and build houses/structures. This is still in an early state but is functioning nicely. We have already used this tool to replace all previous CODEX maps with compatible maps which are freely editable with this tool. Maps are saved in a chunk format and are streamed as necessary by the client. To host your map only takes a static http server. We will provide and maintain an official mapset, but encourage all community involvment in creating, sharing and hosting their own maps!

![](world_creator_stones.png)

## Steam

CODEX is now being developed for the Steam platform which, for our small team, acts as another person to support our backend. They take a chunk of profits but the trade-offs we've decided are well worth it. Steam handes all authentication for our servers, with clustering support. The community servers will be publicly listed on Steam for players to join.

# Gameplay Improvements

The addition of Public Servers is a huge, but we've been making progress improving the gameplay our engine with two very significant updates.

## Network Optimizations

Network movement was refactored into a Server Authority / Client Side Prediction model. This means a more accurate representation of your character's position in the world on your screen, and other player's screens, while providing security against teleport/wall/speed hacking. If you're interested in the technical details the system works similar to what's described [here](https://gabrielgambetta.com/client-server-game-architecture.html).

## Multistory Buildings

Multi-story buildings are now possible with full support of upto 6 levels. Roofs hide when you go under them, including all the items and players on that roof.  While this feature is something to be expected, it was a **big** change to the way the game plays and feels that took a considerable amount of effort. Please be excited for roofs and floors. Thank you.


![](large_tower.png)


# The Future

Now that we have a website up and a place to post regular updates, we can start focusing on getting the game ready enough for some testing. First we will host a game and invite some players to test, as we need to check out the networking changes more thoroughly. After this stage is complete we can discuss where we go next.

If you have any questions, be sure to check out our [FAQ](https://codex.corppor.com/faq) or join us in [Discord](https://discord.com/invite/qvgAHrtq)

# A Big Thanks

A BIG Thank You to everyone that has stuck with us through these patience-trying times and here's to all the fun to come!