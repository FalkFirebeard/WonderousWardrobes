# HyStash

**HyStash 1.4.0 - Hytale 0.7.2 - Falk Interactive Studios**

HyStash is the new name for Wondrous Wardrobes, previously published as **Wonderous Wardrobes**. It is Falk Interactive Studios' standalone storage and inventory expansion mod, turning decorative wardrobes into functional storage while preserving their native appearance and opening/closing behavior.

## Features

- **16 wardrobe variants**, preserving their models, textures and animations.
- **54 inventory slots per wardrobe**, with native transfers and persistent storage.
- Contextual wardrobe spawning and loot that follows supported faction, structure and room contexts.
- Existing recipes, loot weights and empty-spawn chances preserved.
- **220 production prefab overrides** for supported structures.
- Standalone operation with no required third-party dependencies.
- Optional [HyThief 1.4.2](https://www.curseforge.com/hytale/mods/hythief) interoperability for supported owned-container theft interactions.

HyThief recognizes supported owned HyStash wardrobes through native storage mechanics and ownership metadata. With both installed, successful withdrawals can be witnessed and trigger HyThief's existing theft consequences and native pursuit rules. Both mods function independently. Not every wardrobe is owned or every NPC a witness; player-placed wardrobes remain unowned.

## Install and upgrade from Wondrous Wardrobes 1.3.0

1. Back up the affected worlds and close the game/server.
2. Remove or disable the old Wonderous Wardrobes package.
3. Install **HyStash_v1.4.0.zip** from [GitHub releases](https://github.com/FalkFirebeard/WonderousWardrobes/releases/latest) or the [existing CurseForge project](https://www.curseforge.com/hytale/mods/wonderous-wardrobes).
4. Enable **HyStash** in each affected world's mod configuration.
5. Do not run both mod identities together.
6. Load the original world normally.

The identity changes from `FalkFirebeard:Wonderous Wardrobes` to `FalkFirebeard:HyStash`. Existing block/item IDs and storage/ownership formats remain unchanged. Existing wardrobe contents and exact inventory slot positions were preserved in verified upgrade tests, including save, exit and reload. Every possible third-party configuration has not been tested; explicit server/mod references to the old identity need review. [Detailed upgrade instructions](Docs/HYSTASH_UPGRADE.md).

## Existing worlds and compatibility

Requires Hytale **0.7.2** (exact target `=0.7.2`). Existing vanilla wardrobes generated without required container components do not automatically gain functional storage, and previously unowned wardrobes do not automatically gain ownership. Newly generated supported structures receive the established storage and contextual loot behavior. Mods overriding the same wardrobe definitions or prefabs may conflict.

[Release notes](Docs/RELEASE_1.4.0.md) - [Compatibility](Docs/COMPATIBILITY.md) - [HyThief](https://www.curseforge.com/hytale/mods/hythief)

Developed by **Falk Interactive Studios**. Creator: **Falk Firebeard**.
