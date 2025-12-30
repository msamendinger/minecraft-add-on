# Minecraft Bedrock Add-on: Black Dread and Axolotl Beast

This repository is for the creation of a Minecraft Bedrock Edition add-on that introduces two new mobs: the **Black Dread** and the **Axolotl Beast**.

## The Plan

The project will be broken down into the following stages:

1.  **Project Scaffolding:** Create the necessary file and folder structure for a Minecraft Bedrock Add-on, including a Resource Pack and a Behavior Pack.

2.  **Mob Concept and Design:** Define the core characteristics of each new mob. This involves answering questions about their appearance, behavior, and spawning mechanics.

3.  **Black Dread Implementation:**
    *   **Resources:** Create the model, texture, and animations.
    *   **Behavior:** Define its AI, components (health, speed, etc.), and loot drops.

4.  **Axolotl Beast Implementation:**
    *   **Resources:** Create the model, texture, and animations.
    *   **Behavior:** Define its AI, components, and loot drops.

5.  **Localization:** Add in-game names for the mobs and their spawn eggs.

6.  **Testing and Refinement:** Package the add-on, test it in-game, and fix any bugs.

## Mobs

### Black Dread

A fearsome, dark creature. Details to be decided.

### Axolotl Beast

A monstrous version of the cute axolotl. Details to be decided.

## Key Decisions to be Made

To bring these mobs to life, we need to decide on the following for each:

### Appearance
*   What is its overall size, shape, and color scheme?
*   Will it be based on an existing mob's model or have a completely new one?
*   What will its texture look like?

### Behavior
*   **Disposition:** Is it hostile, neutral, or passive towards the player?
*   **Combat:**
    *   What does it attack (players, villagers, other mobs)?
    *   What is its attack style (melee, ranged)?
    *   How much health and attack damage does it have?
    *   Does it have any special abilities (e.g., poison, teleportation)?
*   **Movement:** How does it move (walking, flying, swimming)? What is its speed?

### Spawning
*   In which biomes or dimensions should it appear?
*   What are the conditions for it to spawn (e.g., light level, time of day)?
*   How common or rare should it be?

### Loot
*   What items, if any, does it drop when defeated?
*   How much experience does it grant?

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
