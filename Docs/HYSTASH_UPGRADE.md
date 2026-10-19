# Upgrading to HyStash 1.4.0

HyStash is the continuation of Wondrous Wardrobes, previously published as Wonderous Wardrobes, for Hytale 0.7.2.

1. Back up existing worlds and close Hytale/the server.
2. Remove or disable the old Wonderous Wardrobes package.
3. Install HyStash 1.4.0 (`HyStash_v1.4.0.zip`).
4. Enable HyStash in each affected world's mod configuration.
5. Do not run both mod identities together.
6. Load the original world normally.

The pack identity changes from `FalkFirebeard:Wonderous Wardrobes` to `FalkFirebeard:HyStash`. On servers managed through JSON, disable/remove the old `Mods` entry and enable the new entry while the server is stopped. This is particularly important when `DefaultModsEnabled` is false. Review explicit `RequiredPlugins`, dependency or load-order references to the old identity, together with their version constraints. Retain other world settings.

All existing wardrobe block/item/spawner IDs, 54-slot native container components and ownership metadata remain unchanged. Verified migration tests preserved existing blocks, all item stacks and their exact sorted slots through save, exit and reload. No block or inventory conversion is shipped or required for the verified configuration. This is a configuration-assisted upgrade, with no automatic old-pack alias. Every possible third-party configuration has not been tested.

HyThief 1.4.2 is optional; both mods work independently. Existing unowned wardrobes remain unowned. Existing vanilla wardrobes without required container components do not automatically gain functional storage. Newly generated supported structures retain their contextual storage/loot behavior. Mods replacing the same wardrobe assets may conflict.
