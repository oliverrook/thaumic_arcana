THINGS TO FIX
-

* Some recipes in Thaumonomicon are not being shown properly in the following researches;
  - Bestialchemy
  - Slime Meat

* Fix the wrong required item in the 2/3 stage in Creature Enchant Modification research (maybe this is happening with Enchantment Focusing 2/3 too);
  - The "Enchantment Modifier Powder" with *Normal* effects is shown, but the non-effect powder is the right required item to be consumed (the black one)

* Fix some of the enchanting powders not being able to be placed in pedestals, then, infusions that require them cannot be initiated. You can turn around this bug by using a Hopper or a Dropper aiming directly in the pedestal;

* Fix a bug with Biomancy's draws in the Research Table where the required items to be consumed are NOT getting consumed at all;

* Add recipes to a research in Thaumonomicon (maybe creating a new one) for;
  - Incubated Egg
  - Nutritious Mix
  - Organic Curiosity
  - Vaporous Curiosity
  - Infused Curiosity
  - Animated Curiosity
  - Aura Wood Sapling
  - Research Results
  - All the Infused Slime Balls

* Make (almost) all Infused Slime Balls have a functional effect;
  - And maybe try to get more functional effects from Slime Balls of aspects which came from other addons

* Add some missing items to noted recipes in Thaumonomicon;
  - Incubated Egg's recipe
  - Slime Steak's recipe (?)

* (Maybe) Change the texture for some icon entries in Thaumonomicon;
  - Enchantment Effect > less thin
  - Material Studies: Hay > change to hay bayle
  - Creature Enchant Modifier: Negation > wrong powder

* Fix grammar in Thaumonomicon entries; - ALMOST DONE
  - Some small mistakes; - DONE (I think...)

* Add the Foci Effects' Texts; - DONE
  - thaumic_arcana.enable_creature_enchants.name=Empowerment
  - thaumic_arcana.enable_creature_enchants.text=Gives the property of be enchanted to any creature.

  - thaumic_arcana.disable_creature_enchants.name=Disempowerment
  - thaumic_arcana.disable_creature_enchants.text=Any creature affected become unable to be enchanted.

* Add missing entries; - DONE
  - research.ENCHANT_MODIFICATION@1.text=Creature Modifier - Normal

* Add missing textures; - ALMOST DONE
  - Taint Wine Trunk (the top/bottom texture not showing properly) - DONE
  - Mind Inhibitor - DONE (provisory texture (recolor from mind controller from Explosives Plus))
  - Aura Leaves - DONE (provisory texture)
  - Aura Wood Log (side and top) - DONE (provisory texture)
  - Aura Wood Sapling - DONE (provisory texture)

* Finish some block functionalities:
  - The Aura Wood still renders it the wrong way when the Aura Wood Sapling grows
  - Aura Leaves, Aura Wood Sapling and Aura Wood Log doesn't have a main harvesting tool to be broken easely, nor funcional as pretended yet (expl. Aura Leaves doesn't have transparency, Aura Wood Log isn't counting as wood material and Aura Wood Sapling doesn't seems have been treated as a crop/plant. Also, they doesn't have their respective sounds they should make when placed or broken)

* Fix research
  - In "Infused Slime Tools", it states that any of the five Infused Slimey Tools can be crafted even if the Non-Infused Slimey Tool is damaged, but it can't
  - Because of what happens in the previous line, you can easily think that the pickaxe won't craft because it's bugged and it can't be used to complete "Infused Armor" research
