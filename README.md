# Let There Be More Maces

Fabric mod for Minecraft 1.21.11 (Java 21).

## Kill-upgrade mace
Kill players with a mace to upgrade it through 5 tiers (1, 4, 9, 16, 25 kills). Each tier changes the
texture, adds enchantments and damage, and adds abilities. Tier 5 bans players it kills
(turn off with `BAN_ON_KILL` in `MaceUpgradeMod.java`).

## Boss maces (quests)
| Mace | Quest |
|---|---|
| Warden Mace | Kill a Warden |
| Ender Mace | Defeat the Ender Dragon |
| Nether Mace | Defeat the Wither |

Craft the boss heavy core first, then the mace (heavy core + breeze rod + boss item).
`/maces quests` shows progress. Ops can skip a quest with `/tag <player> add maces_quest_warden`
(or `maces_quest_ender`, `maces_quest_nether`).

## Commands
- `/dummy`: spawns a Carpet fake player (or a Husk) as a PvP dummy. `/dummy clear` removes it.
- `/maces quests`: quest progress.

## Build
Upload `maceupgrade.zip` to the repo. GitHub Actions builds it and attaches `lettherebemoremaces-jar`.
To use your own textures, upload square PNGs (16 to 128 px) named `mace_tier_1.png` ... `mace_tier_5.png`,
`warden_mace.png`, `ender_mace.png`, `nether_mace.png` to the repo's main folder.
