[Pewter](../../index.md) / [com.ejektaflex.pewter.api.core.modifiers](../index.md) / [PewterArmorModifier](./index.md)

# PewterArmorModifier

`abstract class PewterArmorModifier : ArmorModifierTrait, `[`IPewterArmorModifier`](../-i-pewter-armor-modifier.md)

Extend this if you want to create a new armor modifier.

### Parameters

`name` - The unique identifier for this modifier.

`color` - The color of this modifier. Usually specified in hex (0x44AA77)

`The` - max level of the armor modifier

### Constructors

| Name | Summary |
|---|---|
| [&lt;init&gt;](-init-.md) | `PewterArmorModifier(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, color: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, maxLevel: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 0, countPerLevel: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)` = 0, identifier: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = name.toLowerCase().filter { it != ' ' })`<br>Extend this if you want to create a new armor modifier. |

### Properties

| Name | Summary |
|---|---|
| [name](name.md) | `val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)<br>The unique identifier for this modifier. |

### Functions

| Name | Summary |
|---|---|
| [getItemsSafe](get-items-safe.md) | `open fun getItemsSafe(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<ItemStack>>?`<br>[getItems](#) may throw an exception if no items have been specified. This method retrieves all of the items safely. |
| [safeAdd](safe-add.md) | `open fun safeAdd(stack: ItemStack?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html)<br>Safely adds an [ItemStack](#) with which we can create the modifier. |
