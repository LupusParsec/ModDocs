---
title: IPewterModifier - Pewter
---

[Pewter](../../index.html) / [com.ejektaflex.pewter.api.core.modifiers](../index.html) / [IPewterModifier](./index.html)

# IPewterModifier

`interface IPewterModifier : `[`IPewterBaseEffect`](../../com.ejektaflex.pewter.api.core/-i-pewter-base-effect.html)

### Functions

| [configure](configure.html) | `abstract fun configure(): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |
| [getItemsSafe](get-items-safe.html) | `abstract fun getItemsSafe(): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<`[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<ItemStack>>?` |
| [safeAdd](safe-add.html) | `abstract fun safeAdd(stack: ItemStack?): `[`Unit`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-unit/index.html) |

### Inheritors

| [IPewterArmorModifier](../-i-pewter-armor-modifier.html) | `interface IPewterArmorModifier : `[`IPewterModifier`](./index.html) |
| [IPewterToolModifier](../-i-pewter-tool-modifier.html) | `interface IPewterToolModifier : `[`IPewterModifier`](./index.html) |

