---
title: MaterialData - Pewter
---

[Pewter](../../index.html) / [com.ejektaflex.pewter.api.core.materials.stats](../index.html) / [MaterialData](./index.html)

# MaterialData

`class MaterialData`

### Types

| [MatPart](-mat-part/index.html) | `enum class MatPart` |
| [PartType](-part-type/index.html) | `enum class PartType` |

### Constructors

| [&lt;init&gt;](-init-.html) | `MaterialData()` |

### Properties

| [armor](armor.html) | `var armor: `[`ArmorStats`](../-armor-stats/index.html)`?` |
| [color](color.html) | `var color: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [craftable](craftable.html) | `var craftable: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [createMeltingRecipes](create-melting-recipes.html) | `var createMeltingRecipes: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [fluid](fluid.html) | `var fluid: `[`MutableMap`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`>` |
| [fluidNames](fluid-names.html) | `var fluidNames: `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>?` |
| [isCustomMaterial](is-custom-material.html) | `var isCustomMaterial: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [looks](looks.html) | `var looks: `[`MutableMap`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`Float`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-float/index.html)`>` |
| [madeInToolForge](made-in-tool-forge.html) | `var madeInToolForge: `[`Boolean`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-boolean/index.html) |
| [matParts](mat-parts.html) | `var matParts: `[`MutableSet`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-set/index.html)`<`[`MatPart`](-mat-part/index.html)`>` |
| [meltingTemperature](melting-temperature.html) | `var meltingTemperature: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html) |
| [name](name.html) | `var name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |
| [nameLocales](name-locales.html) | `var nameLocales: `[`MutableMap`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>` |
| [smeltingItems](smelting-items.html) | `var smeltingItems: `[`SmeltingStats`](../-smelting-stats/index.html) |
| [smeltingTags](smelting-tags.html) | `var smeltingTags: `[`SmeltingStats`](../-smelting-stats/index.html) |
| [specificTraits](specific-traits.html) | `var specificTraits: `[`MutableMap`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-map/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, `[`MutableList`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-mutable-list/index.html)`<`[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`>>` |
| [tool](tool.html) | `var tool: `[`ToolStats`](../-tool-stats/index.html) |

### Functions

| [registerStats](register-stats.html) | `fun registerStats(m: Material, part: `[`MatPart`](-mat-part/index.html)`): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

