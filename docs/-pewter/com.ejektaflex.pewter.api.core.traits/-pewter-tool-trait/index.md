[Pewter](../../index.md) / [com.ejektaflex.pewter.api.core.traits](../index.md) / [PewterToolTrait](./index.md)

# PewterToolTrait

`abstract class PewterToolTrait : ModifierTrait, `[`IPewterToolTrait`](../-i-pewter-tool-trait.md)

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `PewterToolTrait(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, color: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, identifier: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = name.toLowerCase().filter { it != ' ' })` |

### Properties

| Name | Summary |
|---|---|
| [name](name.md) | `val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| Name | Summary |
|---|---|
| [baseStatsOf](base-stats-of.md) | `fun baseStatsOf(tool: ItemStack?): ToolNBT` |
| [statsOf](stats-of.md) | `fun statsOf(tool: ItemStack?): ToolNBT` |
