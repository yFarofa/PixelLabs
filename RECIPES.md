# 📜 PixelLabs - Custom Recipes & Items

Este documento lista todas as receitas personalizadas disponíveis no modpack **PixelLabs**.

---

## 📋Tabela de Items
| Item           | Descrição|
|---------------------|--------------------|
| Labium Ingot       | Compatível com Silent Gear|
| Master Ball Lid    | Usado para craftar Master Balls|
| Platinum Sheet     | Novo material de crafting|
| Silver Sheet       | Outro novo material de crafting|
| Tyrian Shadow Blend | Material especial com propriedades únicas|

---

## 📋 Tabela de Receitas

| Output | Type | Ingredients |
|--------|------|-------------|
| `projecte:transmutation_table` | Smithing | `projecte:philosophers_stone` + `minecraft:netherite_block` |
| `pixelmon:exp_all` | Smithing | `pixelmon:exp_share` + `thermal:upgrade_augment_3` |
| `pixelmon:exp_all` | Smithing | `pixelmon:exp_share` + `projecte:philosophers_stone` |
| `kubejs:master_ball_lid` | Smithing | `pixelmon:poke_ball_lid (Ultra Ball)` + `kubejs:tyrian_shadow_blend` |
| `pixelmon:poke_ball (Master Ball)` | Shapeless | `createpixelmon:radiant_base` + `kubejs:master_ball_lid` + `minecraft:stone_button` |
| `projecte:transmutation_tablet` | Shaped | `waystones:warp_dust`, `mekanism:teleportation_core`, `thermal:enderium_ingot`, `minecraft:enchanting_table` |
| `pokelucky:poke_phone` | Shapeless | `pixelmon:camera`, `minecraft:glass`, `mekanism:energy_tablet` |
| `pixelmonluckyblock:common_block` | Shaped | `pixelmon:poke_ball`, `minecraft:gold_ingot` |
| `pixelmonluckyblock:master_block` | Shapeless | `pixelmon:fire_gem`, `minecraft:netherite_ingot`, `pixelmon:wishing_piece`, `pixelmon:amethyst`, `minecraft:ender_chest` |
| `pokehaancraftadd:trading_sim` | Shaped | `pixelmon:cooked_red_apricorn`, `pixelmon:poke_ball`, `thermal:iron_gear`, `pixelmon:red_trade_machine`, `minecraft:redstone_block` |
| `pokehaancraftadd:laptop` | Shaped | `pixelmon:cooked_red_apricorn`, `pixelmon:poke_ball`, `thermal:iron_gear`, `pixelmon:red_pc`, `minecraft:redstone_block` |
| `pixelmon:pearl_string` | Shapeless | `pixelmon:pearl` x3 |
| `projecte:philosophers_stone` | Shaped | `mysticalagriculture:supremium_essence`, `minecraft:nether_star`, `pixelmon:wishing_piece`, `minecraft:dragon_egg` |
| `pixelmon:exp_share` | Shaped | `minecraft:ender_pearl`, `thermal:electrum_gear`, `pixelmon:rare_candy`, `pixelmon:l_exp_candy`, `pixelmon:aluminium_plate` |
| `explorerscompass:explorerscompass` | Shaped | `minecraft:ender_pearl`, `fluxnetworks:flux_dust`, `minecraft:netherite_ingot`, `minecraft:compass`, `pixelmon:amethyst`, `thermal:invar_gear` |
| `enchantinginfuser:advanced_enchanting_infuser` | Shaped | `minecraft:book`, `rftoolsbase:infused_diamond`, `minecraft:netherite_ingot`, `thermal:signalum_ingot`, `minecraft:obsidian`, `enchantinginfuser:enchanting_infuser` |
| `enchantinginfuser:enchanting_infuser` | Shaped | `minecraft:book`, `rftoolsbase:infused_diamond`, `minecraft:emerald`, `thermal:signalum_ingot`, `minecraft:obsidian`, `minecraft:enchanting_table` |
| `glangelring:angel_ring` | Shaped | `pixelmon:mental_herb`, `projecte:dark_matter`, `pixelmon:white_herb`, `thermal:lumium_ingot`, `minecraft:elytra`, `minecraft:nether_star` |
| `mekanism:atomic_disassembler` | Shaped | `mekanism:alloy_infused`, `mekanism:energy_tablet`, `mekanism:alloy_atomic`, `minecraft:netherite_pickaxe` |
| `createpixelmon:normal_essence` | Shaped | `mysticalagriculture:inferium_essence`, `minecraft:iron_ingot`, `minecraft:slime_ball` |

---

## 📋Receitas por mod  

### **Create**  
| Tipo                    | Output                           | Ingredientes |
|-------------------------|----------------------------------|--------------|
| **Pressing**            | `pixelmon:aluminium_plate`       | `#forge:ingots/aluminum` |
|                         | `kubejs:silver_sheet`           | `#forge:ingots/silver` |
|                         | `kubejs:platinum_sheet`         | `#forge:ingots/platinum` |
| **Cutting**             | `2x pixelmon:aluminum_base`     | `pixelmon:aluminium_plate` |
|                         | `2x pixelmon:silver_base`       | `kubejs:silver_sheet` |
|                         | `2x pixelmon:platinum_base`     | `kubejs:platinum_sheet` |
|                         | `2x pixelmon:iron_base`         | `create:iron_sheet` |
| **Mixing (Heated)**     | `minecraft:nether_star`         | `4x pixelmon:star_piece` |
|                         | `createpixelmon:legendary_essence` | `createpixelmon:water_essence`, `createpixelmon:fire_essence`, `createpixelmon:grass_essence`, `createpixelmon:electric_essence`, `createpixelmon:psychic_essence` |
| **Mixing (Superheated)**| `kubejs:tyrian_shadow_blend`    | `2x silentgear:tyrian_steel_ingot`, `create:shadow_steel` |
| **Emptying**            | `minecraft:glass_bottle` + `createpixelmon:<fluid>juice_fluid` | `pixelmon:<fluid>_juice` |
| **Filling**             | `createpixelmon:<type>_essence` | `Fluid.of(createpixelmon:<color>juice_fluid, 200)`, `createpixelmon:normal_essence` |

_(Os `<fluid>` e `<type>` representam os elementos: red, yellow, blue, green, pink, purple para sucos e water, fire, grass, electric, psychic para essências.)_

---

### **Mekanism**  
| Tipo       | Output                     | Ingredientes |
|------------|---------------------------|--------------|
| **Enriching** | `kubejs:labium_ingot` | `kubejs:tyrian_shadow_blend` |
| **Purifying** | `ars_nouveau:carbuncle_shards` | `pixelmon:raw_tumblestone` + `mekanism:oxygen (amount: 1)` |

---

### **Thermal Expansion**  
| Tipo       | Output                     | Ingredientes |
|------------|---------------------------|--------------|
| **Smelter** | `pixelmon:gold_bottle_cap` | `potionsmaster:calcinatedgold_powder`, `6x createpixelmon:legendary_essence` (Energia necessária: 120000 RF/FE) |
|  | `pixelmon:silver_bottle_cap` | `potionsmaster:calcinatedsilver_powder`, `createpixelmon:legendary_essence` (Energia necessária: 20000 RF/FE) |
|  | `mekanism:ingot_steel`     | `2x minecraft:coal`, `minecraft:iron_ingot` (Energia necessária: 1000 RF/FE) |

---

## 🛠️ Como Usar?

- **Smithing**: Utilize a `Smithing Table` para combinar os itens indicados.
- **Shapeless**: Combine os ingredientes em qualquer ordem na `Crafting Table`.
- **Shaped**: Siga o formato correto na `Crafting Table`.
- **Pressing**: Coloque o ingrediente indicado no `Mechanical Press` para obter o output.
- **Cutting**: Coloque o ingrediente indicado no `Mechanical Saw` para obter o output.
- **Mixing (Heated)**: Utilize um `Mechanical Mixer` aquecido para combinar os ingredientes e obter o output.
- **Mixing (Superheated)**: Use um `Mechanical Mixer` super aquecido para criar a receita indicada.
- **Emptying**: Combine o ingrediente indicado com um `Glass Bottle` para preencher o frasco com o fluido correspondente.
- **Filling**: Use o `Spout` junto com o fluido na quantidade especificada para obter a essência do tipo desejado.
- **Enriching**: Coloque os ingredientes na `Enrichment Chamber` para criar o output.
- **Purifying**: Utilize a `Purification Chamber` para transformar os ingredientes em um item refinado.
- **Smelter**: Coloque os ingredientes no `Induction Smelter` com a quantidade de energia especificada para fundir os itens.

---

Este documento será atualizado conforme novas receitas forem adicionadas ao modpack.
