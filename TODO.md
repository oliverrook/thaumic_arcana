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
  - One of the mods below is making those infusions IMPOSSIBLE to be initiated; - STILL UNDER INVESTIGATION

       States: 'U' = Unloaded 'L' = Loaded 'C' = Constructed 'H' = Pre-initialized 'I' = Initialized 'J' = Post-initialized 'A' = Available 'D' = Disabled 'E' = Errored
       
       | State  | ID                         | Version                         | Source                                                                 | Signature                                |
       |:------ |:-------------------------- |:------------------------------- |:---------------------------------------------------------------------- |:---------------------------------------- |
       | LCHIJA | minecraft                  | 1.12.2                          | minecraft.jar                                                          | None                                     |
       | LCHIJA | mcp                        | 9.42                            | minecraft.jar                                                          | None                                     |
       | LCHIJA | FML                        | 8.0.99.99                       | forge-1.12.2-14.23.5.2859.jar                                          | e3c3d50c7c986df74c645c0ac54639741c90a557 |
       | LCHIJA | forge                      | 14.23.5.2859                    | forge-1.12.2-14.23.5.2859.jar                                          | e3c3d50c7c986df74c645c0ac54639741c90a557 |
       | LCHIJA | thaumcraft6enhancedpatcher | 1.0.2                           | minecraft.jar                                                          | None                                     |
       | LCHIJA | mixinbooter                | 4.2                             | minecraft.jar                                                          | None                                     |
       | LCHIJA | openmodscore               | 0.12.2                          | minecraft.jar                                                          | None                                     |
       | LCHIJA | foamfixcore                | 7.7.4                           | minecraft.jar                                                          | None                                     |
       | LCHIJA | obfuscate                  | 0.4.2                           | minecraft.jar                                                          | None                                     |
       | LCHIJA | betterbiomeblend           | 1.12.2-1.1.6-forge              | betterbiomeblend-1.12.2-1.1.6-forge.jar                                | None                                     |
       | LCHIJA | voxelmap                   | 1.9.25                          | forgemod_VoxelMap-1.9.28_for_1.12.2.jar                                | None                                     |
       | LCHIJA | damageindicatorsmod        | 1.0                             | [1.12.2]DamageIndicatorsMod-3.5.1.jar                                  | None                                     |
       | LCHIJA | cgm                        | 0.15.4                          | guns-0.15.4-1.12.2.jar                                                 | None                                     |
       | LCHIJA | advancedrifles             | 0.6.0                           | advancedrifles-0.6.0.jar                                               | None                                     |
       | LCHIJA | baubles                    | 1.5.2                           | Baubles-1.12-1.5.2.jar                                                 | None                                     |
       | LCHIJA | thaumcraft                 | 6.1.BETA26                      | Thaumcraft-1.12.2-6.1.BETA26.jar                                       | None                                     |
       | LCHIJA | alembic                    | 1.0.0                           | alembic-1.0.0.jar                                                      | None                                     |
       | LCHIJA | almm                       | 1.1                             | AnotherLiquidMilkMod-1.1.jar                                           | None                                     |
       | LCHIJA | forgelin                   | 1.8.4                           | Forgelin-1.8.4.jar                                                     | None                                     |
       | LCHIJA | thaumcraftresearchloader   | 1.0                             | thaumcraftresearchloader-1.0.jar                                       | None                                     |
       | LCHIJA | thaumic_arcana             | 1.2.0                           | Thaumic+Arcana-1.3.1.jar                                               | None                                     |
       | LCHIJA | jei                        | 4.16.1.301                      | jei_1.12.2-4.16.1.301.jar                                              | None                                     |
       | LCHIJA | appleskin                  | 1.0.14                          | AppleSkin-mc1.12-1.0.14.jar                                            | None                                     |
       | LCHIJA | appliedenergistics2        | rv6-stable-7                    | appliedenergistics2-rv6-stable-7.jar                                   | dfa4d3ac143316c6f32aa1a1beda1e34d42132e5 |
       | LCHIJA | quark                      | r1.6-179                        | Quark-r1.6-179.jar                                                     | None                                     |
       | LCHIJA | autoreglib                 | 1.3-32                          | AutoRegLib-1.3-32.jar                                                  | None                                     |
       | LCHIJA | codechickenlib             | 3.2.3.358                       | CodeChickenLib-1.12.2-3.2.3.358-universal.jar                          | f1850c39b2516232a2108a7bd84d1cb5df93b261 |
       | LCHIJA | avaritia                   | 3.3.0                           | Avaritia-1.12.2-3.3.0.37-universal.jar                                 | None                                     |
       | LCHIJA | baubleshud                 | 5.0.2                           | BaublesHud-1.12.2-5.0.2.jar                                            | None                                     |
       | LCHIJA | baubleshulkerboxes         | 4r                              | BaubleShulkerBoxes-1.12.2-4r.jar                                       | 4d7b29cd19124e986da685107d16ce4b49bc0a97 |
       | LCHIJA | ic2                        | 2.8.1001                        | IC2Classic+1.12-1.5.5.2.1.jar                                          | None                                     |
       | LCHIJA | reborncore                 | 3.19.5                          | RebornCore-1.12.2-3.19.5-universal.jar                                 | None                                     |
       | LCHIJA | techreborn                 | 2.27.3.1084                     | TechReborn-1.12.2-2.27.3.1084-universal.jar                            | 8727a3141c8ec7f173b87aa78b9b9807867c4e6b |
       | LCHIJA | forestry                   | 5.8.2.422                       | forestry_1.12.2-5.8.2.422.jar                                          | None                                     |
       | LCHIJA | beebetteratbees            | 2.0.3                           | beebetteratbees-1.12.2-2.0.3.jar                                       | a0f0b759d895c15ceb3e3bcb5f3c2db7c582edf0 |
       | LCHIJA | betteradvancements         | 0.1.0.77                        | BetterAdvancements-1.12.2-0.1.0.77.jar                                 | None                                     |
       | LCHIJA | betterbuilderswands        | 0.13.2                          | BetterBuildersWands-1.12.2-0.13.2.271+5997513.jar                      | None                                     |
       | LCHIJA | botania                    | r1.10-363                       | Botania+r1.10-363.jar                                                  | None                                     |
       | LCHIJA | patchouli                  | 1.0-23.6                        | Patchouli-1.0-23.6.jar                                                 | None                                     |
       | LCHIJA | bewitchment                | 0.22.63                         | bewitchment-1.12.2-0.0.22.64.jar                                       | None                                     |
       | LCHIJA | guideapi                   | 1.12-2.1.8-63                   | Guide-API-1.12-2.1.8-63.jar                                            | None                                     |
       | LCHIJA | bloodmagic                 | 1.12.2-2.4.3-105                | BloodMagic-1.12.2-2.4.3-105.jar                                        | None                                     |
       | LCHIJA | bookshelf                  | 2.3.590                         | Bookshelf-1.12.2-2.3.590.jar                                           | d476d1b22b218a10d845928d1665d45fce301b27 |
       | LCHIJA | brazier                    | 1.2.0                           | brazier-1.2.0.jar                                                      | None                                     |
       | LCHIJA | bmtr                       | 0.4                             | BringMeTheRings-0.4.jar                                                | None                                     |
       | LCHIJA | chesttransporter           | 2.8.8                           | ChestTransporter-1.12.2-2.8.8.jar                                      | None                                     |
       | LCHIJA | chickenchunks              | 2.4.2.74                        | ChickenChunks-1.12.2-2.4.2.74-universal.jar                            | f1850c39b2516232a2108a7bd84d1cb5df93b261 |
       | LCHIJA | mantle                     | 1.12-1.3.3.55                   | Mantle-1.12-1.3.3.55.jar                                               | None                                     |
       | LCHIJA | tconstruct                 | 1.12.2-2.13.0.183               | TConstruct-1.12.2-2.13.0.183.jar                                       | None                                     |
       | LCHIJA | conarm                     | 1.2.5.10                        | conarm-1.12.2-1.2.5.10.jar                                             | b33d2c8df492beff56d1bbbc92da49b8ab7345a1 |
       | LCHIJA | craftpresence              | 1.8.10                          | CraftPresence-Forge-1.12.2-Release-1.8.10.jar                          | eca02c6a597321ad22340897683951ba5c76720a |
       | LCHIJA | crimsonrevelations         | 0.8                             | crimsonrevelations-0.8.jar                                             | None                                     |
       | LCHIJA | crimsonwarfare             | 1.5                             | crimsonwarfare-1.5.jar                                                 | None                                     |
       | LCHIJA | darkutils                  | 1.8.230                         | DarkUtils-1.12.2-1.8.230.jar                                           | d476d1b22b218a10d845928d1665d45fce301b27 |
       | LCHIJA | disenchanter               | 1.8                             | disenchanter[1.12]1.8.jar                                              | None                                     |
       | LCHIJA | dummycore                  | 2.4.112.5.                      | DummyCoreUnofficial-2.4.112.5.jar                                      | None                                     |
       | LCHIJA | dupefixproject             | 3.1.6                           | DupeFixProject-1.12.2-3.1.6.jar                                        | None                                     |
       | LCHIJA | ic2-classic-spmod          | 0.0.0.0                         | IC2Classic+1.12-1.5.5.2.1.jar                                          | None                                     |
       | LCHIJA | weisscore                  | 0.1.1                           | WeissCore-1.12.2-0.1.1-16.jar                                          | None                                     |
       | LCHIJA | welectromagic              | 0.0.14                          | ElectroMagicToolsIC2C-1.12.2-0.0.14.1-18.jar                           | None                                     |
       | LCHIJA | mysticalmechanics          | 0.18                            | Mystical+Mechanics-0.18.jar                                            | None                                     |
       | LCHIJA | embers                     | 1.18                            | EmbersRekindled-1.18.jar                                               | None                                     |
       | LCHIJA | csb_ench_table             | 1.1.3                           | EnchantingTable-1.12-1.1.3.jar                                         | None                                     |
       | LCHIJA | enchantingwiththaumcraft   | 1.3                             | enchantingwiththaumcraft-1.3.jar                                       | None                                     |
       | LCHIJA | theoneprobe                | 1.4.28                          | theoneprobe-1.12-1.4.28.jar                                            | None                                     |
       | LCHIJA | immersiveengineering       | 0.12-98                         | ImmersiveEngineering-0.12-98.jar                                       | None                                     |
       | LCHIJA | engineeredgolems           | 1.2                             | Engineered+Golems-1.2a.jar                                             | None                                     |
       | LCHIJA | renderlib                  | 1.1.7                           | RenderLib-1.12.2-1.1.7.jar                                             | None                                     |
       | LCHIJA | entityculling              | 6.2.3                           | EntityCulling-1.12.2-6.2.3.jar                                         | None                                     |
       | LCHIJA | ea                         | 1.0.1                           | ExpandedArcanum-1.0.3-UFU.jar                                          | None                                     |
       | LCHIJA | fastleafdecay              | v14                             | FastLeafDecay-v14.jar                                                  | None                                     |
       | LCHIJA | foamfix                    | 0.10.14-1.12.2                  | foamfix-0.10.14-1.12.2.jar                                             | None                                     |
       | LCHIJA | foamguns                   | 0.1.0                           | foamguns-0.1.1.jar                                                     | None                                     |
       | LCHIJA | hammercore                 | 2.0.6.32                        | HammerLib-1.12.2-2.0.6.32.jar                                          | 9f5e2a811a8332a842b34f6967b7db0ac4f24856 |
       | LCHIJA | ic2c_extras                | 1.4.8.3                         | IC2CExtras-1.4.8.3.jar                                                 | None                                     |
       | LCHIJA | igi|thaumcraft             | 1.0a                            | IGI-Thaumcraft-1.0a.jar                                                | None                                     |
       | LCHIJA | lunatriuscore              | 1.2.0.42                        | LunatriusCore-1.12.2-1.2.0.42-universal.jar                            | None                                     |
       | LCHIJA | ingameinfoxml              | 2.8.2.94                        | InGameInfoXML-1.12.2-2.8.2.94-universal.jar                            | None                                     |
       | LCHIJA | inventorytweaks            | 1.63+release.109.220f184        | InventoryTweaks-1.63.jar                                               | 55d2cd4f5f0961410bf7b91ef6c6bf00a766dcbe |
       | LCHIJA | ironchest                  | 1.12.2-7.0.67.844               | ironchest-1.12.2-7.0.72.847.jar                                        | None                                     |
       | LCHIJA | isorropia                  | 0.1.13                          | isorropia-1.12.2-0.1.15-UFU.jar                                        | None                                     |
       | LCHIJA | jeibees                    | 0.9.0.5                         | jeibees-0.9.0.5-mc1.12.2.jar                                           | None                                     |
       | LCHIJA | jeiintegration             | 1.6.0                           | jeiintegration_1.12.2-1.6.0.jar                                        | None                                     |
       | LCHIJA | jeivillagers               | 1.0                             | jeivillagers-1.12-1.0.2.jar                                            | None                                     |
       | LCHIJA | jeri                       | Just Enough Recipe Integrations | JERI-1.12.2-1.1.0.jar                                                  | None                                     |
       | LCHIJA | jetif                      | 1.5.2                           | jetif-1.12.2-1.5.2.jar                                                 | None                                     |
       | LCHIJA | jecalculation              | 1.12.2-3.2.7                    | JustEnoughCalculation-1.12.2-3.2.7.jar                                 | None                                     |
       | LCHIJA | effectinfo                 | 1.0.3                           | JustEnoughEffects-1.0.3.jar                                            | None                                     |
       | LCHIJA | jee                        | 1.0.8                           | JustEnoughEnergistics-1.12.2-1.0.8.jar                                 | None                                     |
       | LCHIJA | jeid                       | 1.0.3-55                        | JustEnoughIDs-1.0.3-55.jar                                             | None                                     |
       | LCHIJA | jeresources                | 0.9.2.60                        | JustEnoughResources-1.12.2-0.9.2.60.jar                                | None                                     |
       | LCHIJA | kjlib                      | 1.0.4                           | kjlib-1.0.4.jar                                                        | None                                     |
       | LCHIJA | legendarytooltips          | 1.1.5                           | LegendaryTooltips-1.12.2-1.1.5.jar                                     | None                                     |
       | LCHIJA | lostmagic                  | 1.0                             | lostmagic-1.0.3.2-UFU.jar                                              | None                                     |
       | LCHIJA | magicbees                  | 1.0                             | MagicBees-1.12.2-3.2.25.jar                                            | None                                     |
       | LCHIJA | manavisualizer             | r1.0-1                          | ManaVisualizer-r1.0-1.jar                                              | None                                     |
       | LCHIJA | mrfm                       | 1.0.0                           | Missing+Recipes+for+Thaumcraft+and+SlashBlade+v.0.0.3.5-UFU-1.12.2.jar | None                                     |
       | LCHIJA | missingtextures            | 1.0.0                           | missingtextures-1.12-1.0.0.jar                                         | None                                     |
       | LCHIJA | mm_lib                     | 2.3.0                           | MMLib-2.3.0.jar                                                        | None                                     |
       | LCHIJA | modnametooltip             | 1.10.1                          | modnametooltip_1.12.2-1.10.1.jar                                       | None                                     |
       | LCHIJA | moreoverlays               | 1.15.1                          | moreoverlays-1.15.1-mc1.12.2.jar                                       | None                                     |
       | LCHIJA | thaumicperiphery           | 0.3.1                           | thaumicperiphery-0.3.1.jar                                             | None                                     |
       | LCHIJA | mystgears                  | 1.1.7                           | mystgears-1.1.7.jar                                                    | None                                     |
       | LCHIJA | netherportalfix            | 5.3.17                          | NetherPortalFix_1.12.1-5.3.17.jar                                      | None                                     |
       | LCHIJA | offlineskins               | 1.12.2-v6                       | OfflineSkins-1.12.2-v6.jar                                             | aaaf83332a11df02406e9f266b1b65c1306f0f76 |
       | LCHIJA | openmods                   | 0.12.2                          | OpenModsLib-1.12.2-0.12.2.jar                                          | d2a9a8e8440196e26a268d1f3ddc01b2e9c572a5 |
       | LCHIJA | openblocks                 | 1.8.1                           | OpenBlocks-1.12.2-1.8.1.jar                                            | d2a9a8e8440196e26a268d1f3ddc01b2e9c572a5 |
       | LCHIJA | parrotpower                | 1.12.2                          | parrotpower-1.3.4.jar                                                  | None                                     |
       | LCHIJA | soot                       | 1.10-hotfix                     | Soot-1.10-hotfix.jar                                                   | None                                     |
       | LCHIJA | pewter                     | 1.4.3                           | Pewter-1.4.3.jar                                                       | None                                     |
       | LCHIJA | thaumicaugmentation        | 1.12.2-2.1.7                    | ThaumicAugmentation-1.12.2-2.1.7.jar                                   | 8f678591ba6f78d579e553a8aa94b4c4766cb13d |
       | LCHIJA | thaumicwonders             | 1.8.2                           | thaumicwonders-1.8.2.jar                                               | None                                     |
       | LCHIJA | xercapaint                 | 1.12.2-1.3                      | xercapaint-1.12.2-1.3.jar                                              | None                                     |
       | LCHIJA | planarartifice             | 1.4.0-pre7                      | planarartifice-1.4.0-pre7.jar                                          | None                                     |
       | LCHIJA | thaumicwands               | 1.2.8                           | thaumicwands-1.2.8.jar                                                 | None                                     |
       | LCHIJA | polymancy                  | 1.0.1                           | polymancy-1.0.1.jar                                                    | None                                     |
       | LCHIJA | rustic                     | 1.1.7                           | rustic-1.1.7.jar                                                       | None                                     |
       | LCHIJA | rusticthaumaturgy          | 4.4a                            | Rustic+Thaumaturgy-4.4b.jar                                            | None                                     |
       | LCHIJA | flammpfeil.slashblade      | mc1.12-r32                      | SlashBlade-mc1.12-r34.jar                                              | None                                     |
       | LCHIJA | slashblade_addon           | 1.6.0                           | SJAP-1.6.0.jar                                                         | None                                     |
       | LCHIJA | solarflux                  | 12.4.11                         | SolarFluxReborn-1.12.2-12.4.11.jar                                     | 9f5e2a811a8332a842b34f6967b7db0ac4f24856 |
       | LCHIJA | spark                      | 1.6.3                           | spark-forge.jar                                                        | None                                     |
       | LCHIJA | spartanhudbaubles          | 1.0.0 Indev 1                   | SpartanHUDBaubles-1.12.2-1.0.0.jar                                     | None                                     |
       | LCHIJA | spartanshields             | 1.5.4                           | SpartanShields-1.12.2-1.5.4.jar                                        | None                                     |
       | LCHIJA | xat                        | 0.31.4                          | Trinkets+and+Baubles-0.31.4.jar                                        | None                                     |
       | LCHIJA | spartanweaponry            | 1.4.1                           | SpartanWeaponry-1.12.2-1.4.1.jar                                       | None                                     |
       | LCHIJA | spartanweaponryarcana      | beta 1.0.3                      | SpartanWeaponryArcana-1.12.2-beta-1.0.3.jar                            | None                                     |
       | LCHIJA | stg                        | 1.12.2-1.2.3                    | stg-1.12.2-1.2.3.jar                                                   | None                                     |
       | LCHIJA | surge                      | 2.0.79                          | Surge-1.12.2-2.0.79.jar                                                | d476d1b22b218a10d845928d1665d45fce301b27 |
       | LCHIJA | thaumicredundancy          | 1.0                             | ThamicRedundancy-1.12.2-1.0.0.jar                                      | None                                     |
       | LCHIJA | thaumcraft6enhanced        | 1.0.2                           | Thaumcraft6Enhanced-1.0.2.jar                                          | None                                     |
       | LCHIJA | tcresearchpatcher          | 1.12.2-1.1.3                    | ThaumcraftResearchPatcher-1.12.2-1.1.3.jar                             | 8f678591ba6f78d579e553a8aa94b4c4766cb13d |
       | LCHIJA | thaumiconeprobe            | 1.0.0                           | thaumic-one-probe-1.12.2-1.0.0.jar                                     | None                                     |
       | LCHIJA | tg                         | 0.1.6.0                         | Thaumic_Gadgets_1.12.2_0.1.6_tb.26.jar                                 | None                                     |
       | LCHIJA | thaumadditions             | 12.7.8                          | ThaumicAdditions-1.12.2-12.7.8.jar                                     | 9f5e2a811a8332a842b34f6967b7db0ac4f24856 |
       | LCHIJA | thaumicbases               | 3.3.500.6r                      | thaumicbases-3.3.500.7r.jar                                            | None                                     |
       | LCHIJA | thaumicbrewing             | 1.0.2                           | thaumicbrewing-1.0.2.jar                                               | None                                     |
       | LCHIJA | thaumicjei                 | 1.6.0                           | ThaumicJEI-1.12.2-1.6.0-27.jar                                         | None                                     |
       | LCHIJA | thaumicenergistics         | 2.2.3                           | thaumicenergistics-v2.2.3-delfayne-fork-SNAPSHOT-2.jar                 | None                                     |
       | LCHIJA | thaumicfixes               | 1.0                             | thaumicfixes-1.0-nolibs.jar                                            | None                                     |
       | LCHIJA | tcinventoryscan            | 2.0.10                          | ThaumicInventoryScanning_1.12.2-2.0.10.jar                             | None                                     |
       | LCHIJA | thaumkatana                | 1.0.0                           | Thaumickatana_V1.0.9.5-UFU_MC1.12.2.jar                                | None                                     |
       | LCHIJA | thaumicrestoration         | 1.5.0                           | ThaumicRestoration-1.5.0.jar                                           | None                                     |
       | LCHIJA | thaumictech                | 1.0.0                           | thaumictech_v1.0.2.2-UFU.jar                                           | None                                     |
       | LCHIJA | thaumicterminal            | 1.0.12                          | ThaumicTerminal-1.0.12.jar                                             | None                                     |
       | LCHIJA | thaumictinkerer            | 1.12.2-5.0-620a0c5              | thaumictinkerer-1.12.2-5.0-620a0c5-v2-UFU.jar                          | None                                     |
       | LCHIJA | keletupack                 | 2.3.0                           | thaumisc-2.3.jar                                                       | None                                     |
       | LCHIJA | thaumtweaks                | 0.3.3                           | thaumtweaks-0.3.3.jar                                                  | None                                     |
       | LCHIJA | lastsmith                  | 2.1.8-1.12.2                    | TLS-2.1.8-1.12.2.jar                                                   | None                                     |
       | LCHIJA | topaddons                  | 1.12.2-1.13.0                   | topaddons-1.12.2-1.13.0.jar                                            | None                                     |
       | LCHIJA | treechopper                | 1.2.4                           | TreeChopper-1.12.2-1.2.4.jar                                           | None                                     |
       | LCHIJA | trm                        | 1.0                             | trm-b2.2-UFU.jar                                                       | None                                     |
       | LCHIJA | vanillafix                 | 1.0.10-150                      | VanillaFix-1.0.10-150.jar                                              | None                                     |
       | LCHIJA | recipehandler              | 0.14                            | YARCF-0.14(1.12.2).jar                                                 | None                                     |
       | LCHIJA | phosphor-lighting          | 1.12.2-0.2.7                    | phosphor-forge-mc1.12.2-0.2.7-universal.jar                            | None                                     |
       | LCHIJA | techreborn_compat          | 1.0.0                           | TechReborn-ModCompatibility-1.12.2-1.4.0.76.jar                        | 8727a3141c8ec7f173b87aa78b9b9807867c4e6b |
       | LCHIJA | weisscoreterminal          | 0.1.1                           | WeissCore-1.12.2-0.1.1-16.jar                                          | None                                     |
