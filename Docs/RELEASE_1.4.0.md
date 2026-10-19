# HyStash 1.4.0 - Hytale 0.7.2

- Wondrous Wardrobes is now **HyStash**, continuing the same project and release history.
- The in-game mod name and identity are now **HyStash** / `FalkFirebeard:HyStash`.
- All **16 wardrobe variants**, **54-slot native storage**, existing appearances and normal interactions are preserved.
- Existing contextual loot, recipes, prefab coverage, loot weights and empty-spawn chances remain unchanged.
- Existing block/item identifiers, inventory contents and ownership metadata are preserved. Upgrade tests retained exact inventory slot arrangements through save, exit and reload.
- Remains standalone, with optional **HyThief 1.4.2** compatibility for supported owned wardrobes.

## Upgrading from Wondrous Wardrobes 1.3.0

Back up your worlds and close the game/server. Remove or disable the old package, install **HyStash_v1.4.0.zip**, enable **HyStash** in each affected world's mod configuration, then load the original world normally. **Do not run both identities together.** Explicit references to `FalkFirebeard:Wonderous Wardrobes` need review/update to `FalkFirebeard:HyStash`. Every third-party configuration has not been tested.

Existing vanilla wardrobes without required container components do not automatically gain storage. Previously unowned wardrobes remain unowned; newly generated supported structures receive the established storage and contextual loot.

Developed by **Falk Interactive Studios**. Creator: **Falk Firebeard**.
