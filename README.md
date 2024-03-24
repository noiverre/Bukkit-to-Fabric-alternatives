# Bukkit to Fabric alternatives
An attempt to find and list the alternatives of popular Bukkit plugins for serverside Fabric environment.

Perhaps you are a Bukkit-based server admin, and stumbled upon Fabric serverside mods by chance, now trying to figure out whether you can re-create your server in Fabric without requiring your players to install mods. This note might be helpful for you

## Disclaimer
I don't endorse any of the mods listed below. Also please find support for each of these mods in their respective support place

This list requires more work to do, as I'm not sure if this is the best writing approach during the time of creation

The first mentioned mods don't mean that it's the better option and the rest are *alternatives*, it's just that the first mentioned mods are the easiest to find during the initial writing of this list 

Try to avoid hybrid Bukkit<->Fabric server softwares, I don't forbid, the choice is yours
- [Cardboard/Banner](https://gist.github.com/Patbox/e44844294c358b614d347d369b0fc3bf)

Some of the listed mods might not be the most performance efficient when compared to other existing mods

Some may require extra steps, see footnotes

_"There is a [better list](https://serverside.infra.link), why creating a new one?"_

This list is focused on finding *replacements* of popular Bukkit plugins to Fabric mods, without listing every serverside mods available in Modrinth/Curseforge

You can also check out these cool lists:
- [Fabric Serverside Mods](https://serverside.infra.link)
- [Optifine Alternatives](https://optifine.alternatives.lambdaurora.dev)
- [Useful Fabric Mod List](https://github.com/TheUsefulLists/UsefulMods)
- [Fabric/Quilt Server Optimization](https://gist.github.com/Obydux/55b967f5dcc00633fe895e5a473363d5)
- [Fabric Client Optimization Guide](https://gist.github.com/HexedHero/aab340a84db51913cb1106c2d85f4e4f)

## Alternatives
You will need [Fabric API](https://modrinth.com/mod/fabric-api) for almost every Fabric mods out there, so install it first

Permissions:
- [LuckPerms](https://modrinth.com/mod/luckperms)
- [Player Roles](https://modrinth.com/mod/player-roles)

Item-based Shops:
- [Universal Shops](https://modrinth.com/mod/universal-shops)

Essentials:
- [Essential Commands](https://modrinth.com/mod/essential-commands)

Bans:
- [Ban Hammer](https://modrinth.com/mod/banhammer)

No Chat Reports:
- [No Chat Reports](https://modrinth.com/mod/no-chat-reports)

Placeholders:
- [Text Placeholder API](https://modrinth.com/mod/placeholder-api)
- [MiniPlaceholders](https://modrinth.com/plugin/miniplaceholders)
  - [Luckperms Expansion](https://modrinth.com/plugin/luckperms-expansion)
  - [Expression Expansion](https://modrinth.com/plugin/expressions-expansion)
  - [Chunk Expansion](https://modrinth.com/plugin/miniplaceholders-chunky-expansion)

Holograms:
- [Holograms](https://modrinth.com/mod/holograms)

Chat Formatter (Colors, Item Displays):
- [Styled Chat](https://modrinth.com/mod/styled-chat)
- [Carbon](https://github.com/Hexaoxide/Carbon)

Discord Chat Bridge:
- [Minecord](https://modrinth.com/mod/minecord)
- [Fabric2Discord](https://modrinth.com/mod/fabric2discord)
- [Discord Integration](https://modrinth.com/plugin/dcintegration)

Scoreboards Formatter:
- [Styled Sidebar](https://modrinth.com/mod/styled-sidebars)

Tab Formatter:
- [Styled Tab](https://modrinth.com/mod/styledplayerlist)
- [TAB](https://modrinth.com/plugin/tab-was-taken)
- [TabTPS](https://modrinth.com/plugin/tabtps)

Nickname Formatter:
- [Styled Nicknames](https://modrinth.com/mod/styled-nicknames)

Server Console Formatter:
- [Better Fabric Console](https://modrinth.com/mod/better-fabric-console)

/plugins:
- [Mods Command](https://modrinth.com/mod/mods-command)

TPS & MSPT Checker:
- [TabTPS](https://modrinth.com/plugin/tabtps)

Skyblock:
- [Skylands](https://modrinth.com/mod/skylands)

NPCs (Citizens, ServersNPC etc)
- [Taterzens](https://modrinth.com/mod/taterzens)
- [Fake Players](https://modrinth.com/mod/fake-players)

Anti Cheats:

*There's no anticheats as good as what Bukkit-based anticheats has to offer, but here are few of them*
- Port of PaperMC patch: [AntiXray](https://modrinth.com/mod/anti-xray)
- [Plymouth: Anti-Xray](https://modrinth.com/mod/plymouth-anti-xray)
- [GolfIV](https://modrinth.com/mod/golfiv)

SkinsRestorer:
- [Fabric Tailor](https://modrinth.com/mod/fabrictailor)
- [SkinRestorer](https://modrinth.com/mod/skinrestorer)

Loggers (CoreProtect, Prism etc):
- [Ledger](https://modrinth.com/mod/ledger)

Profilers (spark, Timings):
- [spark](https://modrinth.com/mod/spark/versions)

World Editing (WorldEdit, VoxelSniper etc)
- [WorldEdit](https://modrinth.com/plugin/worldedit)

Geyser/ProtocolSupport:
- [Geyser](https://modrinth.com/mod/geyser)[^1]
  - [Floodgate](https://modrinth.com/mod/floodgate)
  - [Geyser Skin Support](https://modrinth.com/mod/gsmf)

Custom Blocks, Items, UI (ItemsAdder, Oraxen etc):
- [PolyMc](https://github.com/TheEpicBlock/PolyMc)[^1]
- [Polymer](https://modrinth.com/mod/polymer)[^1][^2]
  - [Enchanting Table & Stonecutter UI Fix](https://modrinth.com/mod/server-ui-fix)

Custom Mob Models (ModelEngine, MythicMobs?):
- [Nylon](https://modrinth.com/mod/nylon)[^3]

Patches/Optimizations:[^11]
- [AntiXray](https://modrinth.com/mod/anti-xray)
- [Alternate Current](https://modrinth.com/mod/alternate-current)
- [Entity View Distance](https://modrinth.com/mod/entity-view-distance)
- [Per Player Mob Spawns](https://github.com/vlad2305m/fabric-per-player-spawns)
- [Proper Mbo Cap Modifier](https://modrinth.com/mod/proper-mobcap-modifier)
- [Recipe Cooldown](https://modrinth.com/mod/recipecooldown)
- [Quickbench](https://modrinth.com/mod/quickbench)
- [Audaki Cart Engine (Faster Minecarts)](https://modrinth.com/mod/audaki-cart-engine)
- [Clumps (Clump XP Orbs)](https://modrinth.com/mod/clumps)
- [Starlight](https://modrinth.com/mod/starlight)[^4]
- [LazyDFU](https://modrinth.com/mod/lazydfu)[^5]
- [FerriteCore](https://modrinth.com/mod/ferrite-core)
- [Memory Leak Fix](https://modrinth.com/mod/memoryleakfix)
- [Ksyxis](https://modrinth.com/mod/ksyxis)
- [Krypton](https://modrinth.com/mod/krypton/versions)
- [Chunkumulator](https://modrinth.com/mod/chunkumulator)[^6]
- [Noisium](https://modrinth.com/mod/noisium)
- [Lithium](https://modrinth.com/mod/lithium)[^7]
- [Faster Random](https://modrinth.com/mod/faster-random)
- [Get It Together, Drops! (Combine Dropped Items)](https://modrinth.com/mod/get-it-together-drops)
- [Concurrent Chunk Management Engine (C2ME)](https://modrinth.com/mod/c2me-fabric/versions)[^8]
- [Fastload](https://modrinth.com/mod/fastload)
- [Very Many Players (VMP)](https://modrinth.com/mod/vmp-fabric)
- [Async Locator](https://modrinth.com/mod/async-locator)[^9]
- [Maps of the Unknown](https://modrinth.com/mod/bettermaps)[^9]
- [Icterine](https://modrinth.com/mod/icterine)
- [Disable Portal Checks](https://modrinth.com/mod/disable-portal-checks)[^10]
- [Optimized Dragon Respawn](https://modrinth.com/mod/chunky-extension)
- [antibat](https://modrinth.com/mod/antibat) Why would you need bats?

Gravestones/Death Chests:
- [Universal Graves](https://modrinth.com/mod/universal-graves)
- [Your Items Are Safe](https://modrinth.com/mod/your-items-are-safe)

Land Claiming (GriefPrevention, RedProtect, etc):
- [Get Off My Lawn ReServed (GOML)](https://modrinth.com/mod/goml-reserved)
- [Flan (Fabric LANd)](https://modrinth.com/mod/flan)
- [Leukocyte](https://modrinth.com/mod/leukocyte)

Container Locking (Lockette, LWC, etc):
- [Hey That's Mine (HTM)](https://modrinth.com/mod/htm)

Image On Map (YAMIPA, ImageFrame, etc)
- [Image2Map](https://modrinth.com/mod/image2map)

BungeeCord/Waterfall Bungeeguard:
- [Fabric Bungeecord Proxy](https://github.com/disymayufei/Fabric-Bungeecord-Proxy)

Velocity Modern Forwarding:
- Should be available on modern versions otherwise you can use this [FabricProxy Lite](https://github.com/OKTW-Network/FabricProxy-Lite)

Chunk Pregenerator (Chunky, WorldBorder, etc):
- [Chunky](https://modrinth.com/plugin/chunky)
  - [Border Expansion](https://modrinth.com/plugin/chunkyborder)
  - [Chunky Auto Start/Stop Extension](https://modrinth.com/mod/chunky-extension)
- [Fabric/Quilt Chunk Pregenerator](https://modrinth.com/mod/fabricquilt-chunk-pregenerator)

[^1]: [PolyMc](https://github.com/TheEpicBlock/PolyMc) and [Polymer](https://modrinth.com/mod/polymer) resourcepacks can not be applied to [Geyser](https://modrinth.com/mod/geyser)
[^2]: [Polymer](https://modrinth.com/mod/polymer) by itself can't do things like ItemsAdder or Oraxen, it's a library to create serverside contents, in which a lot of IA/Oraxen-like mods that uses resourcepacks depends to. For list of the mods, [Polymer Dependants](https://modrinth.com/collection/hvT46U6D), [Polymer Ports and Patches](https://modrinth.com/collection/kXdqNZTO)
[^3]: Requires [Polymer](https://modrinth.com/mod/polymer), you also need to learn [BlockBench](https://www.blockbench.net) and it's plugin [Animated Java](https://animated-java.dev)
[^4]: As of 1.20, Minecraft has rewritten light engine is a similar way to Starlight's, [more on this here](https://gist.github.com/Spottedleaf/6cc1acdd03a9b7ac34699bf5e8f1b85c). So you don't need this on versions above 1.20
[^5]: As of 1.19.4, "Mojang has significantly optimized DFU initialization enough that this mod is no longer necessary in many configurations." So you don't need this on versions above 1.19.4
[^6]: Incompatible with C2ME
[^7]: Some patches lithium offers may break other mods or vanilla behavior, but you can configure them
[^8]: C2ME may increase your server RAM usage possible memory leak [#159](https://github.com/RelativityMC/C2ME-fabric/issues/159) [#208](https://github.com/RelativityMC/C2ME-fabric/issues/208) link to the commit that fixes it [here](https://github.com/RelativityMC/C2ME-fabric/commit/023535551b55ab204bec5aae19660565c9cc7356)
[^9]: Maps of the Unknown description says that "Async Locator: Yes and no. This mod cannot work when enabled with Async Locator if its exploration map and villager trade features are enabled, or you may need to toggle at least the corresponding feature of this here mod. And considering my plans for the future of this mod, they will most probably not be compatible at all on the long term. But until further notice, you may use both while validating the aforementioned conditions."
[^10]: May break nether portal-based farms
[^11]; I don't include [ModernFix](https://modrinth.com/mod/modernfix), [ThreadTweak](https://modrinth.com/mod/threadtweak) (a fork of [Smooth Boot (Fabric)](https://modrinth.com/mod/smoothboot-fabric) which is not required on versions above 1.19.4), [MCMTFabric](https://modrinth.com/mod/mcmtfabric), [Dimensional Threading](https://modrinth.com/mod/dimthread), as it may have issues on low threaded machine servers
