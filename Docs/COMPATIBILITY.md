# Optional HyThief compatibility

Wonderous Wardrobes owns wardrobe assets, generation, storage and native ownership metadata. HyThief owns successful-withdrawal detection, visual witnesses, caught notifications and native NPC responses. Neither mod requires the other, and no bridge plugin is used.

Only supported newly generated locations receive ownership. Eligible contexts include Kweebec (33), Feran (10), Outlander (13), occupied Skeleton structures (157), and 2 shared-tradingpost NEARBY placements. These 215 placement opportunities retain their existing spawn/empty probabilities. Another 221 potential container locations remain unowned or excluded. Goblin, Klop and Breach-specific integration is excluded.

Ownership lives on the persistent container base or its native nonempty spawner outcome, never on decorative multiblock fillers. Four direct Feran base holders explicitly preserve their existing native 54-slot storage component alongside ownership.

Wardrobe item definitions do not receive global ownership, so ordinary player-placed wardrobes remain unowned. Previously generated wardrobes without metadata remain unowned; there is no retroactive ownership migration or PREFAB-instance property system.

Witness coverage follows HyThief's existing supported roles. Not every NPC in an owning faction can detect theft. Opening/browsing, deposits and internal rearrangement do not constitute a successful withdrawal.

Verification includes native generation/storage/persistence and optional-mod matrices, native witnessed notification/guard response, and Falk's real-client confirmation of exactly one caught message and Razorleaf response on a standing witnessed withdrawal. The public 1.3.0 package differs from the verified prerelease only in version metadata.
