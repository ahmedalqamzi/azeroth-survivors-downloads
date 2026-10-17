# Azeroth Survivors — Faster mobs, tougher rares and scaled spell effects

[Download the complete Windows setup](https://github.com/ahmedalqamzi/azeroth-survivors-downloads/releases/download/quality-2026-10-15/AzerothSurvivors-Setup-Windows.zip?v=714ecb4-combat) · [Download the launcher](https://github.com/ahmedalqamzi/azeroth-survivors-downloads/releases/download/quality-2026-10-15/AzerothSurvivors-Launcher-Windows.zip?v=714ecb4-combat)

Existing players: close the game, open your launcher and click Refresh. After the update finishes, click Launch. One cumulative update; no separate patches. Existing Data and account saves are retained. Fresh installs download and verify the original Data, about 5.5 GB.

- Normal mobs now use 80-90% of authored speed, capped at 80% of base player speed (5.6 yards/sec), instead of the previous 50-55%/55% cap.
- Named rares preserve their original level, difficulty and party scaling. They have 8x their undiscounted spawn health and 2x spawned damage, instead of replacing their stats with an unscaled early-wave budget.
- Every cache gives one jewellery pickup. Duplicate independent item rolls from kills, paid chests and challenges are removed. Overflowing Coffer ranks now grant a free reroll chance instead of a second item.
- Spell visual size follows the scaled cast/ground area on host and guests. This includes the replicated cast scale; all party members must update.
- Current Aethus spell and jewellery catalogues replace the previous run rewards, including selected upgrade axes, mixed-quality duplicate scaling and spell-specific relic effects. Portrait cards use large icons, rarity frames, focused effects and mouse or 1/2/3 selection.
- Blessings are removed from offers and stat calculation.
- Run XP payouts are 6x the previous published rate, including solo, co-op and dungeon room rewards.
- Ordinary enemies have lower HP and spawn faster from all sides. Bosses and elites retain separate health budgets. Movement has been increased as described above; pressure still comes from numbers.
- Chests and power-ups are less frequent, with at most three ground power-ups.
- Living connected guests can collect buffs and treasure, use world interactions and buy from merchants. Shared reward offers retain individual selections and the 20-second fallback.
- Permanent armour and weapons go directly into the account bag. They do not create a selection screen or equip during the run; equip them afterwards.
- All four authoritative player movement paths collide with loaded tree, rock and building collision hulls, with sliding and airborne clearance. Decorative models without usable hulls remain passable.
- Bosses and rares have separate named red health bars beneath the timer.
- Paid rerolls cost 100 gold, then 300, 900 and so on, after free uses. Co-op uses the shared purse with owner and revision checks.
- New graphics defaults use 8x anisotropic filtering. Existing explicit settings are respected. This does not establish that Aethus uses a different model pack.

This includes the previous five dungeon adaptations (Ragefire Chasm, Wailing Caverns, Shadowfang Keep, Blackfathom Deeps, The Deadmines), Molten Core, shared Keys and lobby contributions, persistent friends/invites, revive circles, camera modes, automatic Druid forms and batch scrapping. Windows only.

The port follows recovered current-client data and the supplied screenshots. Some special-spell runtime and visual edge cases remain documented adaptations; this is not a byte-for-byte recreation.

Native Windows build completed; 136 focused regression tests passed. Native visual checks use an isolated account. Full combat clears, installer execution and a physical multi-computer party session were not run for this update. These checks do not establish final balance.

All party members must update together: protocol 14.

Build `714ecb4b09a73283bf97c9d929658c516db23ba8`. Executable SHA-256: `3BDDFA89EA2BFA0E01E27E1F3230EC98CBA4BFD6B1E14E8EE8B8AD5F099611C2`.
