![Mirror Logo](https://user-images.githubusercontent.com/16416509/119120944-6db26780-ba5f-11eb-9cdd-fc8500207f4d.png)

[![Download](https://img.shields.io/badge/asset_store-brightgreen.svg)](https://assetstore.unity.com/packages/tools/network/mirror-129321)
[![Documentation](https://img.shields.io/badge/docs-brightgreen.svg)](https://mirror-networking.gitbook.io/)
[![Showcase](https://img.shields.io/badge/showcase-brightgreen.svg)](https://mirror-networking.com/showcase/)
[![Video Tutorials](https://img.shields.io/badge/video_tutorial-brightgreen.svg)](https://mirror-networking.gitbook.io/docs/community-guides/video-tutorials)
[![Forum](https://img.shields.io/badge/forum-brightgreen.svg)](https://forum.unity.com/threads/mirror-networking-for-unity-aka-hlapi-community-edition.425437/)
[![Build](https://img.shields.io/appveyor/ci/vis2k73562/hlapi-community-edition/Mirror.svg)](https://ci.appveyor.com/project/vis2k73562/hlapi-community-edition/branch/mirror)
[![Discord](https://img.shields.io/discord/343440455738064897.svg)](https://discordapp.com/invite/N9QVxbM)
[![release](https://img.shields.io/github/release/vis2k/Mirror.svg)](https://github.com/vis2k/Mirror/releases/latest)
[![License: MIT](https://img.shields.io/badge/License-MIT-brightgreen.svg)](https://github.com/vis2k/Mirror/blob/master/LICENSE)
[![Roadmap](https://img.shields.io/badge/roadmap-blue.svg)](https://trello.com/b/fgAE7Tud)

**It's only the dreamers who ever move mountains.**

<img src="https://user-images.githubusercontent.com/16416509/119117854-3e4e2b80-ba5c-11eb-8236-ce6cfd2b6b07.png" title="Original Concept Art for Games that made us dream. Copyright Blizzard, Blizzard, Riot Games, Joymax in that order."/>

## Mirror
Mirror is a **high level** Networking library for **Unity 2019/2020 LTS**, compatible with different **low level** [Transports](https://github.com/vis2k/Mirror#low-level-transports).

Mirror is for indie games & small [MMOs](https://www.youtube.com/watch?v=mDCNff1S9ZU), made by the developers of [uMMORPG](https://assetstore.unity.com/packages/templates/systems/ummorpg-components-edition-159401) and [Cubica](https://www.youtube.com/watch?v=D_f_MntrLVE).

Mirror is optimized for **ease of use** & **probability of success**.

We needed a networking library that allows us to **[launch our games](https://mirror-networking.com/showcase/)** and **survive the next decade**.

Mirror is **[stable](https://mirror-networking.gitbook.io/docs/general/tests)** & **[production](https://www.oculus.com/experiences/quest/2564158073609422/)** ready.

---
## Free & Open
Mirror is **free & open source**!
* Code: MIT licensed.
* Dedicated Servers: [Anywhere](https://mirror-networking.gitbook.io/docs/guides/server-hosting)!
* Player Hosted: [Free Epic Relay](https://github.com/FakeByte/EpicOnlineTransport)!

We need Mirror for our own games, which is why we will never charge anything. 

Funded only by [Donations](https://github.com/sponsors/vis2k) from our [fantastic community](https://discordapp.com/invite/N9QVxbM) of over 10,000 people.

## Architecture
The **Server & Client** are **ONE project** in order to achieve an order of magnitude gain in productivity.

Making multiplayer games this way is fun & easy. Instead of MonoBehaviour, Mirror provides **NetworkBehaviour** components with:
* **[Server]** / **[Client]** tags for server-only / client-only code
* **[Command]** for Client->Server function calls (e.g. UseItem)
* **[ClientRpc]** / **[TargetRpc]** for Server->Client function calls (e.g. AddChatMessage)
* **[SyncVar]** / SyncList to automatically synchronize variables from Server->Client

## Getting Started
Get **Unity 2020 LTS**, download [Mirror on the Asset Store](https://assetstore.unity.com/packages/tools/network/mirror-129321), open one of the examples & press Play!

Check out our [Documentation](https://mirror-networking.gitbook.io/) to learn how it all works.

If you are migrating from UNET, then please check out our [Migration Guide](https://mirror-networking.gitbook.io/docs/general/migration-guide).

---
## Made with Mirror
### [Population: ONE](https://www.populationonevr.com/)
[![Population: ONE](https://user-images.githubusercontent.com/16416509/178141286-9494c3a8-a4a5-4b06-af2b-b05b66162201.png)](https://www.populationonevr.com/)
The [BigBoxVR](https://www.bigboxvr.com/) team started using Mirror in February 2019 for what eventually became one of the most popular Oculus Rift games.

In addition to [24/7 support](https://github.com/sponsors/vis2k) from the Mirror team, BigBoxVR also hired one of our engineers.

**Population: ONE** was recently [acquired by Facebook](https://uploadvr.com/population-one-facebook-bigbox-acquire/).

### [Nimoyd](https://www.nimoyd.com/)
[![nimoyd_smaller](https://user-images.githubusercontent.com/16416509/178142672-340bac2c-628a-4610-bbf1-8f718cb5b033.jpg)](https://www.nimoyd.com/)
Nudge Nudge Games' first title: the colorful, post-apocalyptic open world sandbox game [Nimoyd](https://store.steampowered.com/app/1313210/Nimoyd__Survival_Sandbox/) is being developed with Mirror.

_Soon to be released for PC & mobile!_

### [A Glimpse of Luna](https://www.glimpse-luna.com/)
[![a glimpse of luna](https://user-images.githubusercontent.com/16416509/178148229-5b619655-055a-4583-a1d3-18455bde631f.jpg)](https://www.glimpse-luna.com/)
[A Glimpse of Luna](https://www.glimpse-luna.com/) - a tactical multiplayer card battle game with the most beautiful concept art & soundtrack.

Made with Mirror by two brothers with [no prior game development](https://www.youtube.com/watch?v=5J2wj8l4pFA&start=12) experience.

### [Inferna](https://inferna.net/)
[![Inferna MMORPG](https://user-images.githubusercontent.com/16416509/178148768-5ba9ea5b-bcf1-4ace-ad7e-591f2185cbd5.jpg)](https://inferna.net/)
One of the first MMORPGs made with Mirror, released in 2019.

An open world experience with over 1000 CCU during its peak, spread across multiple server instances.

### [Samutale](https://www.samutale.com/)
[![samutale](https://user-images.githubusercontent.com/16416509/178149040-b54e0fa1-3c41-4925-8428-efd0526f8d44.jpg)](https://www.samutale.com/)
A sandbox survival samurai MMORPG, originally released in September 2016.

Later on, the Netherlands based Maple Media switched their netcode to Mirror.

### [Untamed Isles](https://store.steampowered.com/app/1823300/Untamed_Isles/)
[![Untamed Isles](https://user-images.githubusercontent.com/16416509/178143679-1c325b54-0938-4e84-97b6-b59db62a51e7.jpg)](https://store.steampowered.com/app/1823300/Untamed_Isles/)
The turn based, monster taming **MMORPG** [Untamed Isles](https://store.steampowered.com/app/1823300/Untamed_Isles/) is currently being developed by [Phat Loot Studios](https://untamedisles.com/about/).

After their successful [Kickstarter](https://www.kickstarter.com/projects/untamedisles/untamed-isles), the New Zealand based studio is aiming for a 2022 release date.

### [Zooba](https://play.google.com/store/apps/details?id=com.wildlife.games.battle.royale.free.zooba&gl=US)
[![Zooba](https://user-images.githubusercontent.com/16416509/178141846-60805ad5-5a6e-4840-8744-5194756c2a6d.jpg)](https://play.google.com/store/apps/details?id=com.wildlife.games.battle.royale.free.zooba&gl=US)
[Wildlife Studio's](https://wildlifestudios.com/) hit Zooba made it to rank #5 of the largest battle royal shooters in the U.S. mobile market.

The game has over **50 million** downloads on [Google Play](https://play.google.com/store/apps/details?id=com.wildlife.games.battle.royale.free.zooba&gl=US), with Wildlife Studios as one of the top 10 largest mobile gaming companies in the world.

### [SCP: Secret Laboratory](https://scpslgame.com/)
[![scp - secret laboratory_smaller](https://user-images.githubusercontent.com/16416509/178142224-413b3455-cdff-472e-b918-4246631af12f.jpg)](https://scpslgame.com/)
[Northwood Studios'](https://store.steampowered.com/developer/NWStudios/about/) first title: the multiplayer horror game SCP: Secret Laboratory was one of Mirror's early adopters.

Released in December 2017, today it has more than **140,000** reviews on [Steam](https://store.steampowered.com/app/700330/SCP_Secret_Laboratory/?curator_clanid=33782778).

### [Naïca Online](https://naicaonline.com/)
[![Naica Online](https://user-images.githubusercontent.com/16416509/178147710-8ed83bbd-1bce-4e14-8465-edfb40af7c7f.png)](https://naicaonline.com/)
[Naïca](https://naicaonline.com/) is a beautiful, free to play 2D pixel art MMORPG.

The [France based team](https://naicaonline.com/en/news/view/1) was one of Mirror's early adopters, releasing their first public beta in November 2020.

### [Laurum Online](https://laurum.online/)
[![Laurum Online](https://user-images.githubusercontent.com/16416509/178149616-3852d198-6fc9-44d5-9f63-da4e52f5546a.jpg)](https://laurum.online/)
[Laurum Online](https://play.google.com/store/apps/details?id=com.project7.project7beta) - a 2D retro mobile MMORPG with over 500,000 downloads on Google Play.

### And many more...
<a href="https://store.steampowered.com/app/719200/The_Wall/"><img src="https://cdn.akamai.steamstatic.com/steam/apps/719200/header.jpg?t=1588105839" height="100" title="The wall"/></a>
<a href="https://store.steampowered.com/app/535630/One_More_Night/"><img src="https://cdn.akamai.steamstatic.com/steam/apps/535630/header.jpg?t=1584831320" height="100" title="One more night"/></a>
<img src="https://i.ytimg.com/vi/D_f_MntrLVE/maxresdefault.jpg" height="100" title="Block story"/>
<a href="https://nightz.io"><img src="https://user-images.githubusercontent.com/16416509/130729336-9c4e95d9-69bc-4410-b894-b2677159a472.jpg" height="100" title="Nightz.io"/></a>
<a href="https://store.steampowered.com/app/1016030/Wawa_United/"><img src="https://user-images.githubusercontent.com/16416509/162982300-c29d89bc-210a-43ef-8cce-6e5555bb09bc.png" height="100" title="Wawa united"/></a>
<a href="https://store.steampowered.com/app/1745640/MACE_Mapinguaris_Temple/"><img src="https://user-images.githubusercontent.com/16416509/166089837-bbecf190-0f06-4c88-910d-1ce87e2f171d.png" title="MACE" height="100"/></a>
<a href="https://www.adversator.com//"><img src="https://user-images.githubusercontent.com/16416509/178641128-37dc270c-bedf-4891-8284-33573d1776b9.jpg" title="Adversator" height="100"/></a>

## Mirror LTS (Long Term Support)

If you use Mirror in production, consider Mirror LTS!
* **Bug fixes** only. 
* **Consistent API**: update any time, without any breaking features.
* Lives along side **Unity 2019** LTS.
* Supported from Sept. 2021 to Sept 2022, depending on feedback.

**Mirror V46 LTS** is available to all [GitHub Sponsors](https://github.com/sponsors/vis2k).

All sponsors are invited to the [Mirror V46 LTS Repository](https://github.com/MirrorNetworking/Mirror-46-LTS) automatically.

## Low Level Transports
* (built in) [KCP](https://github.com/vis2k/kcp2k): reliable UDP
* (built in) [Telepathy](https://github.com/vis2k/Telepathy): TCP
* (built in) [Websockets](https://github.com/MirrorNetworking/SimpleWebTransport): Websockets
* [Ignorance](https://github.com/SoftwareGuy/Ignorance/): ENET UDP
* [LiteNetLib](https://github.com/MirrorNetworking/LiteNetLibTransport/) UDP
* [FizzySteam](https://github.com/Chykary/FizzySteamworks/): SteamNetwork
* [FizzyFacepunch](https://github.com/Chykary/FizzyFacepunch/): SteamNetwork
* [Epic Relay](https://github.com/FakeByte/EpicOnlineTransport): Epic Online Services
* [Bubble](https://github.com/Squaresweets/BubbleTransport): Apple GameCenter
* [Light Reflective Mirror](https://github.com/Derek-R-S/Light-Reflective-Mirror): Self-Hosted Relay
* [Oculus P2P](https://github.com/hyferg/MirrorOculusP2P): Oculus Platform Service

## Benchmarks
* [uMMORPG 480 CCU](https://youtu.be/mDCNff1S9ZU) (worst case)
* [Jesus' Benchmarks](https://docs.google.com/document/d/1GMxcWAz3ePt3RioK8k4erpVSpujMkYje4scOuPwM8Ug/edit?usp=sharing)

## Development & Contributing
Mirror is used **in production** by everything from small indie projects to million dollar funded games that will run for a decade or more.

Therefore it is important for us to follow the [KISS principle](https://en.wikipedia.org/wiki/KISS_principle) in order for our games to survive, so that we can still fix networking bugs 10 years from now if needed.


# Bug Bounty
<img src="https://user-images.githubusercontent.com/16416509/110572995-718b5900-8195-11eb-802c-235c82a03bf7.png" height="150">

A lot of projects use Mirror in production. If you found a critical bug / exploit in Mirror core, please reach out to us in private.
Depending on the severity of the exploit, we offer $50 - $500 for now.
Rewards based on Mirror's [donations](https://github.com/sponsors/vis2k), capped at amount of donations we received that month.

**Specifically we are looking for:**
* Ways to crash a Mirror server
* Ways to exploit a Mirror server
* Ways to leave a Mirror server in undefined state

We are **not** looking for DOS/DDOS attacks. The exploit should be possible with just a couple of network packets, and it should be reproducible.

**Credits / past findings / fixes:**
* 2020, fholm: fuzzing ConnectMessage to stop further connects [[#2397](https://github.com/vis2k/Mirror/pull/2397)]
