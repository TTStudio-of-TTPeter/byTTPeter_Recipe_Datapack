# byTTPeter_Recipe_Datapack
 《我的世界》个人数据包，以完善和想象为主。

This is a project to develop a **personal datapack** for Minecraft(JE). It aims to make the game 'a whole'. Also imagination is a big part of reasons for the creations. Imagination and enhancement!

*`JEI` is highly recommended!*

## Mods in Consideration

- Minecraft itself
- Farmer's Delight
  - Cultural Delights
  - Corn Delight
- Create *(v0.5+)*
- Exnihilo: Sequentia *(Name: Ex Nihilo: Sequentia)*
- PigSteel *(Stopped)*

All the mods can be found on [curseforge.com](https://www.curseforge.com/minecraft/mc-mods)

## Booklet for Players

To View it **online**:

**See `byTTPeter_Recipe changes doc_online.md`**. You may click **[here to view](https://github.com/TTStudio-of-TTPeter/byTTPeter_Recipe_Datapack/blob/main/byTTPeter_Recipe%20changes%20doc_online.md)** or [here to **download**](https://ttstudio-of-ttpeter.github.io/byttpeter_recipe_datapack/byTTPeter_Recipe%20Changes%20doc_online.md).

Also, a [HTML version](https://ttstudio-of-ttpeter.github.io/byttpeter_recipe_datapack/byTTPeter_Recipe%20changes%20doc_online.html) is offered.

To View it **offline**:

Download source pack to see `byTTPeter_Recipe changes doc.md`. The pics referred in the file might not load from Github. So make sure there exists `Changes_pic` folder. To View the Markdown Document, you may use `Typora`. Alternatively, view `byTTPeter_Recipe changes doc.html` in local.

**Offline Booklet is provided [here(Download)](https://github.com/TTStudio-of-TTPeter/byTTPeter_Recipe_Datapack/raw/main/zips_to_upload/byTTPeter_Recipe_Datapack_doczip.zip)!**

## My bad

Sorry for some confusing choices, I actually know nothing about the neccessity of `tags\blocks` and I just made it a copy of `tags\items`.

Also, it seem that `forge:grain` and `forge:crops` didn't taken compressed counterparts into consideration. I don't know if that's true, but in my tags `byttpeter_recipe` **those are counted**.

And please do not care about the sequence of tags of items. The tagging logic is really confusing and I thought it to be random.

## Update Log

### 1.0.2

**Theme: matter recycle(rails, tripwire hook, sheets and blocks)**

Mods Involved:

1. Minecraft itself (None)
2. Create
3. Pigsteel

Change List:

1. [add crushing method] `minecraft:tripwire_hook` to `minecraft:iron_nugget`
2. [add crushing method] `minecraft:rail` to `minecraft:iron_nugget`
3. [add crushing method] `minecraft:powered_rail` to `minecraft:gold_nugget`, `minecraft:redstone`
4. [add crushing method] `minecraft:detector_rail` to `minecraft:iron_nugget`, `minecraft:redstone`, `pigsteel:pigsteel_ingot`
5. [add crushing method] `minecraft:activator_rail` to `minecraft:iron_nugget`, `minecraft:redstone`, `pigsteel:pigsteel_ingot`
6. [add compacting method(heated)] `create:iron_sheet` to `minecraft:iron_block`
7. [add compacting method(heated)] `create:golden_sheet` to `minecraft:gold_block`
8. [add compacting method(heated)] `create:copper_sheet` to `minecraft:copper_block`
9. [add compacting method(heated)] `create:brass_sheet` to `create:brass_block`

**Explanation:**

All new things are manufactured on `Create` stuffs. (`create:crushing_wheel`, `create:mechanical_press`, etc.)

I didn't let sheets have method to ingots directly because that would likely to cause chaos in productions under mechanical press. And smelting type is also applied on fans, it would be wired to see sheets suddenly turn into ingots on belts.

The probabilities are carefully set. Producting won't be too fast.

### 1.0.1

**Theme: Bread Making**

Mods Involved:

1. Farmer's Delight
   1. Cultural Delights
   2. Corn Delight
2. Exnihilo: Sequentia
3. Create

Change List:

1. [add sieve method(water logged)] wheat(`hay_block`), etc.(grain) to `farmersdelight:wheat_dough`
2. [add sieve method(water logged)] wheat(`hay_block`), etc.(grain) to `create:dough`
3. [add sieve method] wheat(`hay_block`), etc.(grain) to `create:wheat_flour`
4. [add tag] `byttpeter_recipe:grain/compressed`
5. [add tag] `byttpeter_recipe:grain`
6. [add tag] `farmersdelight:grain/compressed`
7. [add tag] `farmersdelight:grain`

**Introduction:**

It seems `Farmer's Delight` remove the recipe for bread. As water buckets aren't friendly for producing in the early time, I took advantage of `exnihilo` 's `sieve` to provide new methods.

The probabilities are bound to be pretty and balanced.

**Explanation:**

`grain` terms above refer to items tagged with `byttpeter_recipe:grain/compressed`.

`sieve` refers to those of `Exnihilo`.

For tags, set of `byttpeter_recipe` includes set of `farmersdelight`.

### 1.0.0

**Theme: Origin's Enhancement**

Mods Involved:

1. Minecraft itself (None)

Change List:

1. [add recipe] name tag
2. [add recipe] elytra

**Introduction:**

This initial update focused on MC itself. As `name tag` is a irreplaceable thing to build something sometimes and `elytra` should be reachable for other players in multi-player game, I add recipes for them. I did not change game balance. Everything is of its rarity for it should be.



