---
title: IPewterArmorModifier - Pewter
---

[Pewter](../index.html) / [com.ejektaflex.pewter.api.core.modifiers](index.html) / [IPewterArmorModifier](./-i-pewter-armor-modifier.html)

# IPewterArmorModifier

`interface IPewterArmorModifier : `[`IPewterModifier`](-i-pewter-modifier/index.html)

### Inherited Functions

| [configure](-i-pewter-modifier/configure.html) | `abstract fun configure(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [getItemsSafe](-i-pewter-modifier/get-items-safe.html) | `abstract fun getItemsSafe(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<ItemStack>>?` |
| [safeAdd](-i-pewter-modifier/safe-add.html) | `abstract fun safeAdd(stack: ItemStack?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inheritors

| [PewterArmorModifier](-pewter-armor-modifier/index.html) | `abstract class PewterArmorModifier : ArmorModifierTrait, `[`IPewterArmorModifier`](./-i-pewter-armor-modifier.html)<br>Extend this if you want to create a new armor modifier. |

