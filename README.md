# Minecraft Bedrock Add-on: Black Dread and Axolotl Beast

This repository is for the creation of a Minecraft Bedrock Edition add-on that introduces two new mobs: the **Black Dread** and the **Axolotl Beast**.

## Mobs

### Black Dread

The Black Dread is a hostile creature that lurks in the darkness.

- **Health:** 80
- **Attack Damage:** 5 (Melee)
- **Behavior:**
    - Hostile towards players, witches, and most villagers.
    - Has both a melee attack and a ranged attack where it shoots snowballs.
    - Can breathe and swim in water.
- **Spawning:**
    - Spawns in dark areas (light level 7 or less) on the surface and underground.
    - Spawns in small groups.
- **Loot:**
    - High chance of dropping diamonds.
    - Small chance of dropping a diamond sword or an enchanted book.

### Axolotl Beast

A monstrous and powerful version of the axolotl.

- **Health:** 300
- **Attack Damage:** 7 (Melee)
- **Behavior:**
    - Hostile towards players and villagers.
    - Amphibious: It can move and breathe both on land and in water.
    - Has a melee attack and a ranged attack where it shoots arrows.
- **Spawning:**
    - Spawns on the surface and underwater in any Overworld biome.
- **Loot:** Drops one of a variety of rare items, including:
    - Lava Bucket
    - Piglin Spawn Egg
    - Enchanted Book (Depth Strider I)
    - Potion of Water Breathing
    - Turtle Egg
    - Diamond Chestplate

## How to Build

To use this add-on, you need to package the resource and behavior packs into `.mcpack` files.

**Resource Pack:**

1.  Navigate to the `black_dread_axolotl_beast_RP` folder.
2.  Select all the files and folders inside it.
3.  Compress them into a `.zip` file. Name it `black_dread_axolotl_beast_RP.zip`.
4.  Rename the file to `black_dread_axolotl_beast_RP.mcpack`.

**Behavior Pack:**

1.  Navigate to the `black_dread_axolotl_beast_BP` folder.
2.  Select all the files and folders inside it.
3.  Compress them into a `.zip` file. Name it `black_dread_axolotl_beast_BP.zip`.
4.  Rename the file to `black_dread_axolotl_beast_BP.mcpack`.

**Combined Add-on:**

To create a single `.mcaddon` file that installs both packs at once:

1.  Create a new folder and place the two `.mcpack` files (`black_dread_axolotl_beast_RP.mcpack` and `black_dread_axolotl_beast_BP.mcpack`) inside it.
2.  Compress this new folder into a `.zip` file.
3.  Rename the `.zip` file to `addon.mcaddon`.

Now, when you open the `addon.mcaddon` file, Minecraft will import both the resource and behavior packs.
