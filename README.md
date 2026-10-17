# Azeroth Survivors — Dungeons, Keys and friends

[Download the complete Windows setup](https://github.com/ahmedalqamzi/azeroth-survivors-downloads/releases/download/quality-2026-10-15/AzerothSurvivors-Setup-Windows.zip?v=4b06334-combat)

[Download the small Windows launcher](https://github.com/ahmedalqamzi/azeroth-survivors-downloads/releases/download/quality-2026-10-15/AzerothSurvivors-Launcher-Windows.zip?v=4b06334-combat) — extract it and open Azeroth Survivors Launcher.bat. Choose the game folder, install if missing, and click Launch when ready. Existing launcher users can close the game and click Refresh for this single cumulative update. Data downloads resume; existing Data and saves are retained. Fresh installs download and verify the original Data (about 5.5 GB).

## Four added dungeons

- Ragefire Chasm: levels 3–18.
- Wailing Caverns: levels 17–24.
- Shadowfang Keep: levels 22–30.
- Blackfathom Deeps: levels 24–32.

These join The Deadmines and Molten Core: five dungeons and one raid, playable solo or with up to four players. The new instances use the original indoor maps, ordered boss altars, encounter rosters, corridor waves and boss loot pools. Jump with Space; swim up with Space and dive with Ctrl. Stair support and airborne landing now consistently use the character's capsule footprint, with bounded movement substeps.

## Shared Keys and lobby contributions

- The wallet is called Keys. Existing Dungeon Keys and Raid Keys merge once into that wallet without loss.
- A dungeon costs 2 Keys total; a raid costs 4 Keys total, regardless of party size.
- Each player chooses their own contribution in the lobby. Zero is valid, one person may pay everything, and the total must exactly match the required amount before Ready/Start.
- Changing contributions resets readiness. Each account reserves only its own share; a cancelled entry refunds that share once. Entering gameplay commits the payment.

## Persistent friends and invitations

Open Friends, share a stable friend code once, and accept the request. Accepted contacts are saved separately from progression. While both apps are open, the list shows live presence and hosts can send party invitations; recipients accept directly into the guarded lobby without pasting a new room link. Pending requests, removal, display names and expiring invitations are supported. Room links remain available as a fallback.

## Co-op, UI and performance

- Stand inside a fallen teammate's visible revive circle for four seconds. Progress is shared with the party.
- Consecration and other self-centred ground spells consider nearby enemies even when a distant boss has targeting priority; ground areas may overlap.
- The previous three-player enemy HP reduction of 20% is retained. The host-distance tether remains removed; map walls still apply.
- WoW and Megabonk camera controls are selectable in Settings and remembered.
- Reward cards show their quality clearly, with neutral stat text. Jewellery comparisons include the equipped item's effect.
- Blessings and neutral abilities come from boss rewards alongside equipment, keeping class level-up offers focused. Genuine XP-only bosses also grant their blessing choice; the duplicate Shredder shell does not grant duplicate treasure.
- All living party members can collect eligible treasure; corpses cannot.
- Enemy targeting lists are built only when a caster needs them and reused within that caster's frame. Camera turns no longer rebuild the world-object membership index on every ray. These are work reductions, not a measured FPS claim.

The cumulative package retains stronger bosses, slow enemies and larger swarms, corridor waves, altar summons, automatic combat-driven Druid forms, resource-free classes, batch scrapping, collections and the graphical Windows installer/updater. The launcher checks for updates when opened or refreshed and only starts the game when Launch is clicked.

## Verification

The native Windows build completed. 53 focused checks passed, covering Keys migration and entry refunds, lobby readiness, friends state and encrypted identity, revival, cards, chest rewards, camera controls and instance registration. This includes a live public-relay test with two simultaneous guests. All 28 added dungeon sections passed physical traversal at two frame cadences: 56 traversals using normal movement, jumps and swimming.

Full native combat clears, installer execution and physical multi-computer Friends UI sessions were not run. These checks do not establish final balance. All party members must update together; protocol 12. Windows only.

Build revision: `4b06334b930979549b7a6f620173cfdccb929700`. Executable SHA-256: `A22877AA11141BFBB41F17AF9A380A3304593C5D8E859387FD9D38188B03A356`.
