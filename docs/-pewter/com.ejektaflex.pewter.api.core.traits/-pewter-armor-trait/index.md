---
title: PewterArmorTrait - Pewter
---

[Pewter](../../index.html) / [com.ejektaflex.pewter.api.core.traits](../index.html) / [PewterArmorTrait](./index.html)

# PewterArmorTrait

`open class PewterArmorTrait : AbstractArmorTrait, `[`IPewterArmorTrait`](../-i-pewter-armor-trait.html)

Extend this if you want to create a new Armor trait.

### Constructors

| [&lt;init&gt;](-init-.html) | `PewterArmorTrait(name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)`, color: `[`Int`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-int/index.html)`, identifier: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html)` = name.toLowerCase().filter { it != ' ' })`<br>Extend this if you want to create a new Armor trait. |

### Properties

| [name](name.html) | `val name: `[`String`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin/-string/index.html) |

### Functions

| [armorSetOriginalStats](armor-set-original-stats.html) | `fun armorSetOriginalStats(entity: EntityPlayer): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<ArmorNBT>` |
| [armorSetStats](armor-set-stats.html) | `fun armorSetStats(entity: EntityPlayer): `[`List`](https://kotlinlang.org/api/latest/jvm/stdlib/kotlin.collections/-list/index.html)`<ArmorNBT>` |

