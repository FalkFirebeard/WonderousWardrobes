# HyStash compatibility

HyStash 1.4.0 targets Hytale **=0.7.2**. Its current pack identity is **FalkFirebeard:HyStash**. See [upgrade instructions](HYSTASH_UPGRADE.md) when replacing Wonderous Wardrobes.

## Optional HyThief 1.4.2 compatibility

HyStash provides the wardrobe assets, contextual generation, native 54-slot storage and ownership metadata. HyThief recognizes supported owned wardrobes through native storage mechanics and that metadata, applying its existing successful-withdrawal detection, visual witness, native NPC response and pursuit-access rules. Both mods function independently; neither is a required dependency and no bridge plugin is used.

Supported newly generated locations include selected Kweebec, Feran, Outlander, Skeleton and shared nearby-owned contexts. Loot mappings, weights and empty-spawn chances remain unchanged. Ownership is attached to persistent container bases or native nonempty spawner outcomes, not decorative multiblock fillers. Player-placed wardrobes remain unowned. Previously unmarked wardrobes do not automatically gain ownership, and not every NPC is a witness.

Opening/browsing, deposits and rearranging are not successful withdrawals. Witness coverage and pursuit behavior follow HyThief's supported native roles and states. Special/scripted NPC configurations may require separate compatibility work.

## Existing saves and other mods

Block/item identifiers, container serialization and ownership components remain unchanged. Verified upgrade tests retained existing wardrobe contents and exact slot positions through save, exit and reload. Review explicit references to the former pack identity when upgrading. Every possible third-party configuration has not been tested.

Existing vanilla wardrobes without container components do not automatically gain storage. Other mods overriding the same wardrobe definitions or prefabs may conflict. The current release keeps the existing 16 variants and does not replace other furniture categories.
