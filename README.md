## How It Works

The process from purchase to prize is a simple, multi-step flow:

1. **Crafting:** With a `cash card` (with sufficient funds) and a smart device (`smartphone`, `laptop`, etc.) in your possession, open the crafting menu (`&`). Lootbox recipes can be found in the `OTHER` category.
2. **Purchase:** Crafting a lootbox will take 1 minute and consume a certain amount of money from your `cash card`. The corresponding lootbox item will appear in your inventory.
3. **Placement:** Activate (`a`) the lootbox item from your inventory. This will prompt you to place it on an adjacent tile. The item will be consumed, and a physical lootbox will appear on the ground.
4. **Opening:** The placed lootbox is essentially a static 1 HP object. Attack it with any weapon (or your fists) to destroy it.
5. **Loot!:** Upon destruction, the lootbox will drop its contents onto the tile it occupied.

## The Lootboxes

There are nine types of lootboxes, each with a specific theme, cost, and loot table. Prices are listed in pre-Cataclysm US Dollars.

### Ammo Lootbox
*   **Cost:** $4,000
*   **Contents:** A wide variety of ammunition types.
*   **Loot Logic:** You are guaranteed to receive one random stack of ammo. You then have two separate 30% chances to obtain two additional random stacks.
*   **Loot Set:** Sourced from the `rng_ammo` item group.

### Batteries Lootbox
*   **Cost:** $3,000
*   **Contents:** A random variety of batteries and power cells.
*   **Loot Logic:** You are guaranteed one random battery type. You then have two separate 20% chances to receive more.
*   **Loot Set:** Sourced from the `rng_batteries` item group.

### Bionics Lootbox
*   **Cost:** $8,000
*   **Contents:** CBMs (Consumer Bionic Modules).
*   **Loot Logic:** You are guaranteed to receive one random CBM from the standard set. You have a 20% chance of receiving a second standard CBM, and a 10% chance of receiving a rare/powerful CBM from the `bionics_op` group.
*   **Loot Set:** Sourced from the basic (`vanilla`) item groups `bionics` and `bionics_op`.

### Drinks Lootbox
*   **Cost:** $2,000
*   **Contents:** A large quantity of various sealed beverages, both alcoholic and non-alcoholic.
*   **Loot Logic:** Guaranteed one drop of a random beverage (in a stack of 2 to 5). Two additional 30% chances for more stacks.
*   **Loot Set:** Sourced from the `rng_drinks` item group.

### Explosives Lootbox
*   **Cost:** $6,000
*   **Contents:** Grenades, bombs, and other explosive devices.
*   **Loot Logic:** Guaranteed one drop of explosives. Two additional 20% chances for more.
*   **Loot Set:** Sourced from the `rng_explosives` item group.

### Food Lootbox
*   **Cost:** $2,000
*   **Contents:** A huge variety of preserved and sealed food items.
*   **Loot Logic:** Guaranteed one drop of food. Two additional 30% chances for more.
*   **Loot Set:** Sourced from the `rng_food` item group.

### Guns Lootbox
*   **Cost:** $8,000
*   **Contents:** A fully loaded firearm.
*   **Loot Logic:** You are guaranteed to receive one random, fully loaded firearm. You then have two separate 15% chances for additional firearms.
*   **Loot Set:** Sourced from the `rng_gun` item group.

### Medicine Lootbox
*   **Cost:** $4,000
*   **Contents:** Medical supplies, from bandages and antiseptic to powerful drugs and stimulants.
*   **Loot Logic:** Guaranteed one type of medical item. Two separate 25% chances for more.
*   **Loot Set:** Sourced from the `rng_meds` item group.

### Serums Lootbox
*   **Cost:** $6,000
*   **Contents:** Mutagenic and purifying serums.
*   **Loot Logic:** Guaranteed one random serum. Two additional 20% chances for more.
*   **Loot Set:** Sourced from the `rng_serums` item group.

## FAQ

**Q: Why does the lootbox spawn as a monster?**
A: The game engine has a robust system for handling monster deaths and loot, but no direct system for an item to be "opened" to generate loot from complex tables. By linking the use of an item to the spawning of a 1 HP monster, we can leverage the powerful `death_drops` system.

**Q: Is this mod balanced?**
A: Not in the traditional sense. It is designed as a fun, optional money sink for those bored with vending machines. The prices are intentionally high to reflect the potential for powerful rewards and to prevent it from being a primary source of gear in the early or mid-game.
