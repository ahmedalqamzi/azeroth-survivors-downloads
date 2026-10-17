# Azeroth Survivors — Windows launcher and boss rewards update

[Download the complete Windows setup](https://github.com/ahmedalqamzi/azeroth-survivors-downloads/releases/download/quality-2026-10-15/AzerothSurvivors-Setup-Windows.zip?v=35f94dc-combat)

[Download the small Windows launcher](https://github.com/ahmedalqamzi/azeroth-survivors-downloads/releases/download/quality-2026-10-15/AzerothSurvivors-Launcher-Windows.zip?v=35f94dc-combat) — extract it, open Azeroth Survivors Launcher.bat, choose your game folder, then click Install if needed and Launch when ready. It resumes interrupted Data downloads and updates existing games when opened. Installation and updates never launch the game automatically.

One cumulative package includes the game and all previously shipped updates. No separate patches are required. Extract the ZIP, close the game, run Setup.bat, and select your existing game folder. Existing Data and saves are retained. Fresh installations automatically download and verify the original Data files (about 5.5 GB).

## Launcher fix

Fixed the Windows PowerShell status-file replacement crash. The launcher reads current update metadata through GitHub to avoid stale download hashes. Installer rollback uses an explicit backup path compatible with Windows PowerShell. The observational Check action completes; installer and gameplay execution remain deferred.

## Combat changes

- Defeat the earlier zone bosses before summoning the final altar. A final-boss kill alone cannot skip the other encounters or grant a clear.
- Early altar summons retain their scheduled health, damage and level. Summoning does not advance the shared run clock. There is no minimum run timer.
- Outdoor enemies have 50% more baseline health and 15% more damage on Normal. The ordinary health floor also increases 50%, making floor-limited opening enemies 2.25 times as durable as the previous build.
- Movement speeds remain slow; difficulty still scales above this new Normal baseline.
- Deadmines boss health increases sixfold; Sneed rises from 2,600 to 15,600 base HP. Molten Core boss health increases twelvefold. Both receive higher contact-damage budgets.
- Dungeon trash has a separate HP floor that rises with room progress. Waves and recurring larger swarms continue along the passage until the next boss encounter begins. Survivors remain part of that room's clear requirement.
- Dungeon bosses require activating their current altar with T. Corridor waves continue until activation, and all encounters remain ordered. In co-op the host validates each player's altar interaction.
- Druid forms follow successful Feral combat abilities automatically; Dash sprints without flipping the persistent form. Form bonuses retain a separate cooldown.
- The Windows launcher checks for published updates when opened, installs missing game files and reuses existing Data and saves.
- The launcher now has a native desktop window with folder selection, installation/download progress and an explicit Launch button. Existing installations update automatically; installation and updates never start the game themselves.
- The Armory now has visible Select items, Select all visible and Scrap selected (N) controls with one confirmation for the batch. Equipped gear is excluded.
- Normal level-up offers focus on class abilities and their upgrades. Blessings and neutral upgrades are separate boss rewards alongside equipment and treasure, with independent party choices.

All existing content and four-player co-op remain included. The Deadmines and Molten Core are the current indoor Survivors adaptations. Ragefire Chasm, Wailing Caverns, Shadowfang Keep and Blackfathom Deeps remain in development and are not included in this balance release. Windows only.

Native Windows compilation completed. Gameplay testing and installer execution remain deferred at the user's request; this is not a claim of verified balance or full instance clears. All party members must use this updated package. Protocol 10.

Build revision: `35f94dc303ce84dc6faff4341178f8efc22bd34b`. Executable SHA-256: `2B15D1F6FC03D675CDA651C428E0192B8E32FB40951276C1696183F690AF31EB`.
