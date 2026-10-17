# Azeroth Survivors — Friends controls and opening pressure

[Download the complete Windows setup](https://github.com/ahmedalqamzi/azeroth-survivors-downloads/releases/download/quality-2026-10-15/AzerothSurvivors-Setup-Windows.zip?v=e343d41-combat)

[Download the small Windows launcher](https://github.com/ahmedalqamzi/azeroth-survivors-downloads/releases/download/quality-2026-10-15/AzerothSurvivors-Launcher-Windows.zip?v=e343d41-combat) — extract it and open Azeroth Survivors Launcher.bat. Choose the game folder, install if missing, and click Launch when ready. Existing launcher users can close the game and click Refresh for this single cumulative update. Data downloads resume; existing Data and saves are retained. Fresh installs download and verify the original Data (about 5.5 GB).

## Friends controls and gameplay fixes

- Open Multiplayer → Friends / Invite. Separate Friends, Requests, Add friend and My profile tabs replace the shared text buffer. Code and name inputs have independent focus, paste and selection. UI presses are accepted when their interaction arrives after the raw mouse edge; holding a button cannot submit repeatedly.
- Invite to party creates a room when solo and sends as soon as its connection is ready. Recipients choose Join party. Multiple pending invitations are retained while connecting, up to the three guest seats.
- Slow solo openings receive extra earned wisp XP while below level 5 and behind the 30-second-per-level marks. Healthy openings, parties, dungeons and later progression keep their existing XP. Waiting alone awards nothing.
- Outdoor packs use alternating interception lanes and more forward refills. Periodic rings lean into the movement heading, while spawn safety distance, crowd-control rules and normal movement speeds remain intact. Bodies spread farther apart. This requires playtesting for final balance.
- Jewellery drafts now guarantee a useful option with partial loadouts too: fill an empty seat or upgrade an equipped identity. Exact physical drops and saturated effects retain their existing rules.
- Lingering Whirlwind ticks retain the fully scaled cast radius, including Spell Area, matching the main hit.

## Four included dungeons

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

The native Windows build completed. 52 focused regression checks passed for Friends controls, party entry points, social state, opening XP, enemy movement, Warrior abilities and jewellery offers. The previous public-relay proof and 56 dungeon route traversals remain applicable; those unchanged systems were not rerun for this hotfix.

Full native combat clears, installer execution and physical multi-computer Friends UI sessions were not run. Friends panel screenshots use an isolated account and actual native rendering. These checks do not establish final balance. All party members must update together; protocol 12. Windows only.

Build revision: `e343d419fdefeae334d47ac08236c75c6f3156f2`. Executable SHA-256: `CA4827950A88922A9BF86B6BFDFAAB903B686AAAC9BC1A0EC39AC41DE900173E`.
