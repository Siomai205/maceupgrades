# Let There Be More Maces

Fabric mod for Minecraft 1.21.11 (Java 21).

## Features
- Keeps the original five-tier mace progression.
- Adds three boss-themed maces with custom icons and active/passive effects:
  - **Warden Mace**: sculk shockwave, Darkness, lifesteal.
  - **Ender Mace**: sneak-right-click teleport, Dragon Burst, levitation.
  - **Nether Mace**: Wither burst, Wither effect and fire.
- Adds three craftable themed Heavy Cores.
- Each boss quest is a Minecraft advancement. Defeating the Warden, Ender Dragon, or Wither unlocks that theme's Heavy Core and mace recipes.
- Removes the previous max-tier player-ban behavior.

## Build
The repository workflow extracts `maceupgrade.zip`, copies the five tier textures, and builds the Fabric project using Java 21 and Gradle 9.2.1. Download the artifact named `let-there-be-more-maces` from the Actions run.

## Notes
The new mace textures are original 16x16 pixel-art placeholders. Ability balance can be adjusted in `MaceAbilities.java`.
