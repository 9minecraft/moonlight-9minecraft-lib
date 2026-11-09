# Moonlight 9minecraft Lib — Run Complex Mods Without Errors

Moonlight 9minecraft Lib provides a background toolkit that helps other mods run properly in your game. It works as a core library, meaning it adds no blocks, items, or mobs of its own. You only need to install this library when another mod asks for it. It powers popular additions like the Supplementaries family of mods. The code runs quietly behind the scenes to handle complex tasks like custom map markers, villager trades, and fluid systems so other mods work without errors.

## What this build is

An unofficial rebuild of **MehVahdJukaar**, **xelbayria**'s original work, kept running on current Minecraft releases by 9Minecraft Studios. Not affiliated with the original author and not endorsed by them.

Most of the porting work sits in the mixin layer. Each Minecraft release moves or renames the methods this mod hooks into, so the hooks are re-pointed and re-tested against that version rather than rewritten. The behaviour underneath is upstream's and is deliberately left alone — that is the part that makes the mod feel right, and it is not ours to redesign.

## Source code

Upstream terms are **Supplementaries Team License v.1.5**, so the port tree is not published here. This repository is documentation. Questions about the build go to **9minecraft.net@gmail.com**.

## Versions

| Minecraft | Loader |
|---|---|
| 26.3 | Fabric, NeoForge |
| 26.2 | Fabric, NeoForge |

## Getting the built mod

Install steps, the dependency list, the screenshot gallery and what changed in each release are kept together on the download page:

[9minecraft.net/moonlight-9minecraft-lib](https://www.9minecraft.net/moonlight-9minecraft-lib/)

## Credits

Original work by **MehVahdJukaar**, **xelbayria**. Port and maintenance by 9Minecraft Studios. Licensed Supplementaries Team License v.1.5; the upstream licence text ships inside every build.
